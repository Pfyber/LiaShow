<!--
author: Workshop Demo
email: 
language: en
narrator: US English Female
comment: A hands-on gallery of possibilities for vocational and general education. External embeds require internet access.
import: https://raw.githubusercontent.com/liaTemplates/jscad/master/README.md
import: https://raw.githubusercontent.com/liaTemplates/KekuleJS/master/README.md
import: https://raw.githubusercontent.com/LiaTemplates/JSXGraph/main/README.md
import: https://raw.githubusercontent.com/MichaelMarkert/LiaScript_DragAndDrop_Template/refs/heads/main/README.md
-->

# The Magic Learning Lab

> **Four teachers. One text file. A whole interactive classroom.**
>
> This isn't a slideshow *about* interactive learning. **It IS the interactive learning material.**

**Workshop mission:** Pick a station. Touch something. Change something. Make a prediction. Then reveal how it was made.

*Demonstration requires an internet connection for external simulations, images, video and templates. If an external provider is unavailable, move to the next station.*

## 1 · The object you can turn (engineering)

**Don't show learners a flat picture of a component. Hand them a model.**

Rotate this mount. Look through the central hole. Could you manufacture it? What would you change to make it lighter?

```javascript @JSCAD
const { cuboid, cylinder } = require('@jscad/modeling').primitives;
const { subtract, union } = require('@jscad/modeling').booleans;
const { translate } = require('@jscad/modeling').transforms;
const main = () => {
  const base = cuboid({ size: [70, 48, 8] });
  const boss = translate([0,0,8], cylinder({ radius: 13, height: 16 }));
  const bores = [[-27,-17],[27,-17],[-27,17],[27,17]].map(([x,y]) =>
    translate([x,y,0], cylinder({radius: 3.5, height: 30})));
  const centerHole = translate([0,0,8], cylinder({ radius: 7.5, height: 30 }));
  return subtract(union(base,boss),centerHole,...bores);
};
module.exports = { main };
```

**Teacher prompt:** Which dimensions matter for function, and which are design choices?

### The part is now editable

Change `size: 24` to `size: 40`, run it again, and inspect what happens.

```javascript
const { cube } = require('@jscad/modeling').primitives;
const main = () => cube({ size: 24 });
module.exports = { main };
```
@JSCAD.eval

---

## 2 · A complete laboratory behind a link (electrotechnics)

**Try a real circuit instead of watching a teacher draw one.** Drag components, change resistance, and use the meters.

??[Open the Circuit Construction Kit simulation](https://phet.colorado.edu/sims/html/circuit-construction-kit-dc/latest/circuit-construction-kit-dc_en.html)

**Challenge:** Build a battery, a resistor, and an ammeter in series. What happens to current if you double the resistance?

- [( )] It doubles.
- [(X)] It decreases (for the same supply voltage).
- [( )] It does not change.

[[?]] Think about the relation between voltage, resistance, and current.

> **Takeaway:** Existing PhET simulations can sit inside the same learning journey as explanations and assessments.

---

## 3 · Chemistry: a clickable periodic table

**A periodic table that responds.** Click an element to explore its identity.

@Kekule.periodicTable

Now find *one alkaline earth metal* and *one noble gas*. How does their placement help predict behavior?

### From symbols to molecular structures

The same library can render 2D molecular structure without generating and managing image files.

```xml @Kekule.molecule2d
<cml xmlns="http://www.xml-cml.org/schema">
  <molecule id="ethanol">
    <atomArray>
      <atom id="c1" elementType="C" x2="0" y2="0"/>
      <atom id="c2" elementType="C" x2="1.3" y2="0"/>
      <atom id="o1" elementType="O" x2="2.5" y2="0.6"/>
    </atomArray>
    <bondArray>
      <bond id="b1" order="S" atomRefs2="c1 c2"/>
      <bond id="b2" order="S" atomRefs2="c2 o1"/>
    </bondArray>
  </molecule>
</cml>
```

**Teacher prompt:** What properties of the molecule are *not* conveyed by its 2D skeleton?

---

## 4 · Change the world and see the curve (nature / ecology)

**The story:** A lake receives extra nutrients. Algae grow fast, then level off as resources become limiting.

Drag the growth rate and carrying capacity. What does the graph tell you that a paragraph cannot?

```javascript @JSX.Graph
const k = board.create('slider', [[-7,-6],[0,-6],[50,180,350]], {name:'capacity'});
const r = board.create('slider', [[-7,-7],[0,-7],[0.1,0.45,1.1]], {name:'growth'});
board.create('functiongraph', [
  (x) => k.Value() / (1 + ((k.Value()-12)/12) * Math.exp(-r.Value()*x)), 0, 20
]);
```

**Prediction:** As growth rate increases, does the carrying capacity change?

- [( )] Yes, it always increases.
- [(X)] No, the curve approaches the same capacity more quickly.
- [( )] The population becomes negative.

> *Modeling note:* This is an idealized logistic population model, not a complete lake ecosystem model.

---

## 5 · Images become a gallery (nature)

**A tiny field guide** — click the photos to inspect them. This is not a special gallery plugin; LiaScript makes an image-only paragraph into a gallery.

![Honeybee](https://images.unsplash.com/photo-1471943311424-646960669fbc?w=1000 "Honeybee and pollination")
![Mushroom](https://images.unsplash.com/photo-1504545102780-26774c1bb073?w=1000 "Fungi and decomposition")
![Forest](https://images.unsplash.com/photo-1448375240586-882707db888b?w=1000 "Forest ecosystem")

**Field challenge:** For each image, propose one question a pupil could investigate outdoors.

---

## 6 · A lesson that speaks (English)

**Switch on LiaScript's narration / read-aloud controls.** Listen to the passage before you read it. Then identify the tense.

> When we arrived at the station, the train **had already left**. We **waited** for the next one and **called** our friends.

Which event happened first?

- [(X)] The train left.
- [( )] We arrived.
- [( )] We called our friends.

### Fill in natural language, not just multiple-choice

By the time the scientist arrived, the experiment had already [[started]].

### A dropdown embedded in a sentence

If I [[(were) | was | be]] you, I would check the evidence first.

**Teacher prompt:** Ask students to write an alternate ending using the past perfect at least once.

---

## 7 · A video, exactly where the question belongs

**Learning design:** Instead of assigning 'watch this 20-minute video,' use a short segment and place your own learning task immediately below.

!?[How do vaccines work? — TED-Ed](https://www.youtube.com/watch?v=rb7TVW77ZCs)

**Identify every statement that describes an immune response.**

- [[X]] Immune cells can recognize antigens.
- [[X]] Memory cells can support faster responses later.
- [[ ]] Every vaccination produces identical protection in all people.
- [[ ]] Antibiotics are what produce immune memory.

[[?]] Distinguish innate responses, adaptive responses, and the action of antibiotics.

> For *timestamped interactive video questions*, embed an H5P Interactive Video activity instead; that's a separate tool, not a native video feature.

---

## 8 · Quizzes are not one format (all subjects)

### A matrix: classify, don't guess

Match each example to its best category.

| Example | Chemical change | Physical change |
| :-- | :-: | :-: |
| Iron rusting | [(X)] | [( )] |
| Ice melting | [( )] | [(X)] |
| Paper burning | [(X)] | [( )] |

### A number with feedback

A 12 V source powers a 6 Ω resistor. Find current in amperes.

[[2]]

[[?]] Use Ohm's law and include amperes in your reasoning.

### Drag it into the right sequence

Arrange the stages of a simple investigation from first to last.

@dragdroporder(@uid, Question|Hypothesis|Experiment|Analysis|Conclusion, Question|Hypothesis|Experiment|Analysis|Conclusion)

### A short self-check on one screen

**Select all examples of renewable energy sources.**

- [[X]] Solar
- [[X]] Wind
- [[ ]] Coal
- [[ ]] Natural gas

> **The point:** A teacher can choose the assessment *interaction* based on the thinking being tested: recall, classification, sequence, calculation, or explanation.

---

## 9 · Borrow entire interactive activities (H5P)

**You do not have to rebuild every learning widget.** Embed existing H5P learning objects inside your course.

<iframe src="https://h5p.org/h5p/embed/1216" width="100%" height="440" frameborder="0" allowfullscreen="allowfullscreen" title="Embedded H5P activity"></iframe>

**Important limitation:** Scores inside an H5P iframe are *not automatically recorded as LiaScript quiz results*.

---

## 10 · The final magic trick: reveal the source

Everything in this experience is plain text with a handful of extensions:

```markdown
# A lesson

![A field photo](https://example.org/photo.jpg)

What does the image show?

- [(X)] A bee
- [( )] A butterfly

[[?]] Examine the wing shape.
```

A different type of learning aid can be a **3D CAD model**, an **embedded simulator**, a **periodic table**, a **live chart**, a **gallery**, a **narrated lesson**, a **video**, a **quiz**, or an **external H5P activity**. Yet a teacher can keep the content in one versionable `.md` document.

### Exit ticket — pick your next experiment

- [( )] Turn an existing worksheet into an interactive lesson.
- [( )] Embed a simulation and ask prediction questions.
- [( )] Make a field guide with images and narration.
- [( )] Build a reusable subject-specific widget.

*There is no correct answer to this exit ticket; it's a conversation starter.*

---

## Presenter notes (do not spend workshop time reading this slide)

1. Open in LiaScript and switch to slideshow view.
2. Start with rotating the 3D model. Hand over the mouse.
3. Have an electrical teacher change the circuit live.
4. Let a chemistry teacher find an element on the periodic table.
5. Invite the nature teacher to change the ecological curve.
6. Have the English teacher use narration and the tense exercise.
7. Show the image gallery and video briefly.
8. Rapid-fire the *different* quiz types.
9. Reveal the Markdown source and ask: **Could you maintain this yourself?**

**Technical checks before presenting:** Check imported macro URLs and access to PhET, YouTube, Unsplash, H5P, and JSCAD on the venue network. Some content embeds are blocked by institutional filters or provider policies. LiaScript syntax is based on documented examples, but this whole showcase has not been manually browser-tested end-to-end.

**Sources:** https://liascript.github.io/ · https://liascript.github.io/blog/jscad-3d-cad-in-liascript/ · https://liascript.github.io/blog/kekulejs-chemistry-in-liascript/ · https://liascript.github.io/blog/jsxgraph-interactive-math-in-liascript/ · https://liascript.github.io/blog/h5p-content-in-liascript/

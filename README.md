# motion software

Giving motion to your still designs

First brief description: 
Idea:
Name: Motioner / MotionGiver / AnimateIt
It must do: It gives motion to your designs based on your descriptions, and lets you adjust as you want

The Making:
Export: (n layers of fidelity) After Effects script (.jsx) (?)
Lives in: a web page
Built with: HTML file

The system:
In: text + file (SVG or adobe file)
Rules: ?
Controls: ?
Out: a series of windows with different options and approaches to give motion to your design

The edges:
Looks like: (folder)
Never: never change the original design, never create something that is not changeable, never make decisions or you without letting you know, don’t make it a traditional animation software (keyframes….) it should be easier more immediate and more fun
Done when:  you know it works because it creates a (always changeable) file with the motions you decided and edited and you can download it and open it on an animation software and everything works




Export
Your "done when" says the file must open in animation software and stay changeable, so I'd export in layers of fidelity:
1. Lottie JSON (main format). It keeps keyframes as editable data. It opens in Adobe softwares (through the LottieFiles plugin), LottieFiles Creator, and web/mobile players.
2. SVG with CSS or SMIL animation. It is a plain text file, so it is editable even in a code editor, and it works in any browser.
3. After Effects script (.jsx). It rebuilds your layers and keyframes inside AE, so everything is a normal editable keyframe there.
4. Project file (.motioner.json). This is your own format: the original design reference plus every motion you chose. You can reopen it in Motioner and keep editing.
5. Previews only (GIF/MP4/WebM). These are not changeable, so I'd label them "preview, not editable" to respect your "never create something that is not changeable" rule.

Rules
* The original is read-only. Motion lives in a separate layer that points to the design's elements by ID.
* Nothing is applied without approval. Each suggestion appears as an option with a plain-language explanation, and you accept or reject it.
* Every motion is data, never baked. Each one is stored as keyframes, duration, easing, delay and so on, so you can reopen and change any of them.
* Always offer 3 approaches per element (for example subtle / balanced / bold), with a label saying what each does.
* Ask when unsure. If a description is ambiguous ("make it feel alive"), Motioner asks or shows options instead of guessing.
* Keep a visible decision log: what was changed, why, and who decided (you or a suggestion you accepted).
* Undo and redo are always available.
* Test the export. Before download, Motioner checks that the file is valid, then reopens it in its own preview to confirm it matches.
* Respect "reduced motion" by offering a calmer version.
* Name things clearly. Layers keep their original names so they're recognizable in other software.

Controls
* Per element: select, lock, include or exclude
* Motion: type (fade, move, scale, rotate, bounce...), intensity slider, direction
* Timing: duration, delay, stagger (offset between elements), loop, speed
* Easing: presets plus a curve editor
* Timeline: play, pause, scrub, and drag keyframes
* Compare: toggle original vs. animated
* Document: canvas size, FPS, undo and redo
* Export: format picker, with a warning on non-editable formats

SECOND brief description:W

Idea:
Name: Motioner / MotionGiver / AnimateIt
It must do: It gives motion to your designs based on your descriptions, and lets you adjust as you want

The Making:
Export: Lottie JSON, After Effects script (.jsx), GIF/MP4
Lives in: a web page
Built with: HTML file

The system:
In: text + file (SVG or adobe file)
Out: a series of windows with different options and approaches to give motion to your design
Controls:
* Controlling: select, lock
* Motion: type (fade, move, scale, rotate, bounce...), intensity, direction
* Timing: duration, speed
* Postproduction: saturation, contrast, brightness…
* Timeline: play, pause, edit
* Compare: compare different animation options
* Export: format picker (with a warning on non-editable formats)

Rules
* Nothing is applied without approval. Each suggestion appears as an option with a plain-language explanation, and you accept or reject it, or modify it.
* Every motion is data, never baked. Each one is stored as keyframes, duration, easing, delay and so on, so you can reopen and change any of them.
* Always offer 3 approaches per element 
* Ask when unsure. If a description is ambiguous, it asks or shows options instead of guessing.
* Keep a visible decision history: what was changed, why, and who decided (you or a suggestion you accepted).
* Undo and redo are always available.
* Test the export. Before download, it checks that the file is valid, then reopens it in its own preview to confirm it matches.
* Name things clearly. Layers keep their original names so they're recognizable in other software.

The edges:
Looks like: (folder)
Never: never change the original design, never create something that is not changeable, never make decisions or you without letting you know, don’t make it a traditional animation software (keyframes….) it should be easier more immediate and more fun
Done when:  you know it works because it creates a (always changeable) file with the motions you decided and edited and you can download it and open it on an animation software and everything works
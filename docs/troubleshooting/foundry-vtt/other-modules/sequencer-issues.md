---
title: Sequencer
parent: Other Modules
grand_parent: Foundry VTT
layout: page
---

***

### Is there a documentation for Sequencer?

> _Yes! Here is the link to the [Sequencer wiki](https://fantasycomputer.works/FoundryVTT-Sequencer/#/)_

***

### I can't dismiss an animation

> Use the Sequencer Effect Viewer to end one or all effects on the scene [insert image]
> If that doesn't work, it might be: 
> * an issue with Automated Animations [insert link]
> * a deeper issue with Sequencer probably coming from Automated Animations.
>  Use this command line in a macro to reset the flags on the scene:
```js 
canvas.scene.unsetFlags("sequencer", "effects")
```
then refresh (F5)

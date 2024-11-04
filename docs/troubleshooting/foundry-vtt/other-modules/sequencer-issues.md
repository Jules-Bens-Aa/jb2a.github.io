---
title: Sequencer
parent: Other Modules
ancestor: Troubleshooting
layout: page
---

# Sequencer - Troubleshooting

* _[Sequencer wiki](https://fantasycomputer.works/FoundryVTT-Sequencer/#/)_
* _[General Troubleshooting steps](insert_link)_

***

### I can't dismiss an animation

> Use the Sequencer Effect Viewer to end one or all effects on the scene ![](../../../../assets/images/insert_image.png)

> If that doesn't work, it might be: 
> * an issue with Automated Animations [](insert_link)
> * a deeper issue with Sequencer probably coming from Automated Animations.
>  Use this command line in a macro to reset the flags on the scene:
```js 
canvas.scene.unsetFlags("sequencer", "effects")
```
then refresh (F5)

Patching:

```
patch -R < <name of the patch>.def
```
Interesting
https://dwm.suckless.org/patches/restoreafterrestart/
Need to add save state: https://unix.stackexchange.com/questions/176243/save-windows-state-in-dwm

Hint from reddit post:

 I generally don't like "recommend me some patches" posts because they are inevitably subjective.

This is a bit different though and I know that you have been around the block when it comes to dwm so I'll share my experiences.

There are many ways to be productive. In this context I'm considering productivity as in actually having a day job, using your window manager and only that window manager to perform that day job, and at the end of the day not get fired.

Here are some of the features that I have come to value in terms of productivity, in no particular order.

zoomswap. If you have more than two tiled windows open then having all of them rotate around when zooming is something I'd consider distracting and maybe even disorienting. Having only the two relevant windows swap places and leaving all other windows untouched makes for a less disrupting workflow.

awesomebar. Not necessarily for the window titles, but for the ability to minimize / iconify / hide windows. As a practical example sometimes when dealing with time critical issues I end up with way too many windows open. I may be in a position where I can't close all of those windows just yet, but I still need to clear some room to continue. Being able to just hide some of those windows to quickly free up some space can be very helpful.

namedscratchpads (or renamedscratchpads). Having windows that you can bring into and out of view using a single keybinding can make for a rather potent workflow. I have about seven or so scratchpads. By default most these will spawn terminals as that is what I use most often, but I also have a couple for notes. Being able to assign a window to a scratchpad during runtime is nice, but not a must.

stacker (or masterstacker). This depends very much on your workflow and what you are doing, but being able to focus directly on tiled clients using dedicated keybindings can be quite efficient. With masterstacker you can also swap any two tiled clients just like with zoomswap.

pertag + monitorrules. pertag needs no introduction, everyone knows that one despite it going against the general idea of how dwm is to be used. The way I have my WM set up is that I have designated tags for different tasks, and those tags have a specific layout, and I have client rules that places on said tags / monitors. The end effect is that I practically never change layouts, because it is already what it is supposed to be on every tag on every monitor.

focusonnetactive (and/or switchtag). If you started a new program then you probably did so for a reason. Being able to see that window straight away despite it starting on a different tag due to client rules is a clear improvement when it comes to productivity.

mark. No standalone patch for this (the one on the suckless site does something very different). The general idea is that you can mark one or more clients and then perform an action on all of them. My most common use case is to do MOD+a to select all visible clients then do MOD+q to kill them all. 

 I generally don't like "recommend me some patches" posts because they are inevitably subjective.

This is a bit different though and I know that you have been around the block when it comes to dwm so I'll share my experiences.

There are many ways to be productive. In this context I'm considering productivity as in actually having a day job, using your window manager and only that window manager to perform that day job, and at the end of the day not get fired.

Here are some of the features that I have come to value in terms of productivity, in no particular order.

zoomswap. If you have more than two tiled windows open then having all of them rotate around when zooming is something I'd consider distracting and maybe even disorienting. Having only the two relevant windows swap places and leaving all other windows untouched makes for a less disrupting workflow.

awesomebar. Not necessarily for the window titles, but for the ability to minimize / iconify / hide windows. As a practical example sometimes when dealing with time critical issues I end up with way too many windows open. I may be in a position where I can't close all of those windows just yet, but I still need to clear some room to continue. Being able to just hide some of those windows to quickly free up some space can be very helpful.

namedscratchpads (or renamedscratchpads). Having windows that you can bring into and out of view using a single keybinding can make for a rather potent workflow. I have about seven or so scratchpads. By default most these will spawn terminals as that is what I use most often, but I also have a couple for notes. Being able to assign a window to a scratchpad during runtime is nice, but not a must.

stacker (or masterstacker). This depends very much on your workflow and what you are doing, but being able to focus directly on tiled clients using dedicated keybindings can be quite efficient. With masterstacker you can also swap any two tiled clients just like with zoomswap.

pertag + monitorrules. pertag needs no introduction, everyone knows that one despite it going against the general idea of how dwm is to be used. The way I have my WM set up is that I have designated tags for different tasks, and those tags have a specific layout, and I have client rules that places on said tags / monitors. The end effect is that I practically never change layouts, because it is already what it is supposed to be on every tag on every monitor.

focusonnetactive (and/or switchtag). If you started a new program then you probably did so for a reason. Being able to see that window straight away despite it starting on a different tag due to client rules is a clear improvement when it comes to productivity.

mark. No standalone patch for this (the one on the suckless site does something very different). The general idea is that you can mark one or more clients and then perform an action on all of them. My most common use case is to do MOD+a to select all visible clients then do MOD+q to kill them all. 

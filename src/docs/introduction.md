![META](authors:Nicolas "Duduf" Dufresne;license:GNU-FDL;copyright:2021;updated:2021/07/30)

# DuGR Help

![](img/group_timeline.png)

Dugr lets you to tag the layers so they belong to groups. Those groups are listed in the panel, and it is easy to isolate them in the composition, change their attributes, etc.

## Tabs and group lists

There are two tabs on the panel:

- ![](img/icons/prop_group.svg){: style="width:20px;"} ***Properties*** allows you to select the layers by type, property or hierarchy.
- ![](img/icons/layer_group.svg){: style="width:20px;"} ***Groups*** contains the list of tags/custom groups you've added.

![](img/tabs.png)

You can select the group of layers you need to manipulate from these two lists.

The ![](img/icons/invert.svg){: style="width:20px;"} ***Invert*** button can be used to manipulate layers **not** contained in the selected groups.

## Isolation

The top line buttons are toggles to isolate the layers belonging to the selected groups.

- ![](img/icons/isolate.svg){: style="width:20px;"} ***Isolate*** isolates the layer both in the timeline and the comp viewer panel. Layers outside of selected groups are both hidden and set to shy mode.
- ![](img/icons/isolate_tl.svg){: style="width:20px;"} ***Timeline*** isolates the layer only in the timeline. Layers outside of selected groups are set to shy mode.
- ![](img/icons/isolate_comp.svg){: style="width:20px;"} ***Comp*** isolates the layer only in the comp viewer panel. Layers outside of selected groups are hidden.
- ![](img/icons/pin.svg){: style="width:20px;"} The *pin* button toggles the ***Interactive*** or ***Sticky*** mode. When checked, the isolation is updated as soon as you change the group selection. When disabled, you have to manually change the isolation mode after changing group selection. With heavy compositions containing a lot of layers, keeping it disabled improves the performance.

## Layer properties

The two middle lines of small icons can be used to quickly change the usual properties of the layers contained in the selected groups.

The extra ![](img/icons/select.svg){: style="width:12px;"} *arrow* icon selects the layers contained in the selected groups.

## Managing groups

!![](img/groups.png)

On the ***custom groups tab***, a few extra buttons allow you to create, edit and remove groups.

### Layer buttons

- ![](img/icons/add_layer.svg){: style="width:20px;"} ***Add selected layer*** to the current groups.
- ![](img/icons/layer_info.svg){: style="width:20px;"} ***Select groups*** the current layers belong to.
- ![](img/icons/remove_layer.svg){: style="width:20px;"} ***Remove selected layers*** from the current group.

### Group buttons

- ![](img/icons/add.svg){: style="width:20px;"} ***Create group***.
- ![](img/icons/edit.svg){: style="width:20px;"} ***Rename group***.
- ![](img/icons/remove.svg){: style="width:20px;"} ***Remove group***.

### Bottom line icons

At the bottom line of the panel, a few icons are always there if you need them.

- ![](img/icons/bug.svg){: style="width:20px;"} Post a ***Bug Report*** if something goes wrong.
- ![](img/icons/feature.svg){: style="width:20px;"} Post a ***Feature Request*** if you have a good idea to share.
- ![](img/icons/settings.svg){: style="width:20px;"} Go to the ***Settings panel*** to customize the script.
- ![](img/icons/help.svg){: style="width:20px;"} Come here if you need ***Help***.
- ![](img/icons/heart.svg){: style="width:20px;"} Click this ***if you like*** *DuGR*!.
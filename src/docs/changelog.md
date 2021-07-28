# Duik NoName Changelog

This is the list of what has changed since the previous major version of Dugr (*3.02*).

## ▹ 4.0.0-Beta

4.0.0 will be the next major release of *DuGR* for *After Effects*, which brings a lot of changes.

### New

- **New User Interface**: Along with a complete code refactor, *DuGR* underwent a complete UI redesign. Performance (loading time and isolation) has been improved (*a lot*), *DuGR* now fits better in the interface of After Effects, it is more discreet and let you focus on your work.
- *DuGR* now uses **markers** to identify groups on the layers. Note that due to this important change (which improves performance and user experience), it won't be able to detect groups made by previous versions and by older versions of *Duik*.
- New dynamic groups: **orphans** and **have children** to help you manage your layer parenting.
- New ***Ignored*** group; use it to set some layers to be ignored no matter what.

### Improvements

- **Complete code refactor**: *DuGR* is easier to maintain, code is better organizezd, performance has been improved a lot...
- *DuGR* now remembers which panel you were on and restores it when opening it.
- Added the *Selected*, *All layers* and *Grouped* groups in the custom groups panel.

### Fixes

### Other changes

- We've finally dropped support of *After Effects CS6*, sorry, it was too much work to keep compatibility for too few users. *CS6* (*v11.0.2*) dates back to October 2012, it's time to update! *DuGR* should now work on all versions of After Effects starting with *After Effects CC* (*v12.0*, July 2013).
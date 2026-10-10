I thought I was going crazy. I saw some committed changes to my animations in another project that I didn't intend. Here is how to reproduce the issue:

1. Clone the repo
1. Open `project.godot` in Godot (I used 4.7.2.stable.fedora.ed1daf0bf)
1. Open `main.tscn` as the open scene
1. Rename `test_body` to `buggy_body`
1. Save the scene
1. Confirm that `RESET.tres` and `bend.tres` have unstaged changes.

If this is an intended side-effect of inherited scenes, please disregard.

# Floppy Gizmo

## Windows beta 0.4.77

One installer covers Maya 2025, 2026.3 and 2027.1. The same release has a Godot 4.5.1 / 4.7.2 add-on and a Move preview for Unreal Engine 5.9.0 Preview 2. The Unreal preview draws elastic arrows while you drag the editor’s regular Move handles.

[Download the Windows betas, read installation steps and see known issues](https://github.com/Depuiseau/floppy-gizmo-downloads/releases/tag/v0.4.77-windows-beta.1)

## Earlier standalone Maya 2025 plug-in

[Download FloppyGizmo.mll for Maya 2025 on Windows x64](https://github.com/Depuiseau/floppy-gizmo-downloads/raw/refs/heads/main/FloppyGizmo.mll)

Standalone build **0.4.36**.

1. Copy the file into your Maya user plug-ins folder, usually Documents/maya/2025/plug-ins. Create the folder if necessary.
2. In Maya, open **Windows → Settings/Preferences → Plug-in Manager**. Find FloppyGizmo.mll and enable **Loaded**. Use **Browse** if needed. Select **Auto load** to add the menu at future startups.
3. Choose **Floppy Gizmo → Settings** in the main menu. This starts the tool and opens its controls. You can reopen them with the same menu or run `floppyGizmoSettings` in the MEL command line.

This build is unsigned. Follow your studio's plug-in policy.

## Test it and leave feedback

Try it on a cube in a new scene. Drag a colored plane, rotate one full turn, change scale, then undo. Include the editor version and beta tag so someone can repeat the test.

[Report a bug](https://github.com/Depuiseau/floppy-gizmo-downloads/issues/new?template=bug.yml) · [Suggest an improvement](https://github.com/Depuiseau/floppy-gizmo-downloads/issues/new?template=idea.yml) · [Share a test result](https://github.com/Depuiseau/floppy-gizmo-downloads/issues/new?template=test.yml)

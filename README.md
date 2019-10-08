>*Note: This repository primarily serves as a submodule for `LittleEngine` (and is bound by the same licence), but is completely standalone and free to be used in any other projects.*

### LittleEngine SysDialog

*Copyright 2019 Karn Kaul*

Features:
- MessageBox / X11 implementations as a system dialogue box
- Supports three responses (as MessageBox buttons / X11 keypresses)

Usage:
- Prepare `DialogueData` and call `CreateSystemDialogue(std::move(data))`

CMake:
  - Set `SOURCES` to existing source file list and include `SysDialog.cmake` before creating the target

Compile Units:
- SysDialog.cpp

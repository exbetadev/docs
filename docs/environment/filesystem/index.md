---
icon: lucide/folder
---

---
tags:
  - Filesystem
---

# Filesystem

Read and write files inside the executor workspace.

| Function | Description |
| --- | --- |
| [`readfile`](readfile/index.md) | Reads a file from the workspace. |
| [`writefile`](writefile/index.md) | Writes a file, creating any missing parent folders. |
| [`appendfile`](appendfile/index.md) | Appends data to the end of a file. |
| [`listfiles`](listfiles/index.md) | Lists the entries of a workspace folder. |
| [`isfile`](isfile/index.md) | Checks whether a file exists. |
| [`isfolder`](isfolder/index.md) | Checks whether a folder exists. |
| [`makefolder`](makefolder/index.md) | Creates a folder, including missing parents. |
| [`delfile`](delfile/index.md) | Deletes a file. |
| [`delfolder`](delfolder/index.md) | Deletes a folder and its contents. |
| [`loadfile`](loadfile/index.md) | Compiles a workspace file into a function without running it. |
| [`dofile`](dofile/index.md) | Compiles a workspace file and runs it immediately. |
| [`getcustomasset`](getcustomasset/index.md) | Publishes a workspace file and returns a URI the game can load. |

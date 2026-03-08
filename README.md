[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) [![Discord Banner](https://discord.com/api/guilds/1479794793394737152/widget.png?style=banner1](https://discord.gg/fhwfqZzEJf)

# List of FOSS Obsidian Clones

## Tier 1 (fully Obsidian-compatible)
To be listed here, the FOSS Obsidian clone must work with Obsidian vaults **without requiring a custom importer or conversion step**. This means same Markdown and JSON Canvas formats[^1], same bidirectionnal link handling[^2] and same free folder structure for notes and their attachments. Other features are optional.

[^1]: a JSON Canvas implementation must at least appears on the roadmap if not presently implemented.
[^2]: both short path and long path in wikilinks must be understood and updated.

- **[Lokus](https://github.com/lokus-ai/lokus)** > cross-platform, canvas supported, graph and base views supported
- **[Otterly](https://github.com/ajkdrag/otterly)** > cross-platform, canvas planned
- **[Cherit](https://github.com/Keshav-writes-code/Cherit)** > cross-platform, canvas planned?
- **[Foam](https://github.com/foambubble/foam)** > VS Code plugin, not cross-platform

## Tier 2 (opinionated)
Implementations listed here require an importer step for Obsidian vaults because they have hard-coded the attachment folder or they decided to enforce long path for all wikilinks. They are still required to have a free folder structure for notes and the same file formats as Obsidian.

- [**HelixNotes**](https://codeberg.org/ArkHost/HelixNotes) > cross-platform, UpNote-like UI

# Supporting Tech Stack

## UI Frameworks
- **[Tauri](https://github.com/tauri-apps/tauri)**  
- **[React](https://github.com/facebook/react)**
- **[Svelte](https://github.com/sveltejs/svelte)**

## Markdown Editors
- **[CodeMirror](https://github.com/codemirror/dev)**  
- **[ProseMirror](https://github.com/ProseMirror/prosemirror)**
 
## Canvas Editors
- **[Excalidraw](https://github.com/excalidraw/excalidraw)**  
- **[TLDraw](https://github.com/tldraw/tldraw)**
- **[React & Svelte Flow](https://github.com/xyflow/xyflow)**
- **[Throwdown JSON Canvas editor](https://github.com/staticeys/Throwdown)** (experimental)

## File Format Specs and Tooling
- **[Obsidian-Flavored Markdown](https://help.obsidian.md/obsidian-flavored-markdown)**
- **[reMark](https://github.com/remarkjs/remark)**
- **[JSON Canvas](https://github.com/obsidianmd/jsoncanvas)**
- **[Open Canvas Working Group's serialization tools](https://github.com/ocwg)**


# Suggestions

Open an issue if you know new Obsidian clones or technologies supporting their creation!

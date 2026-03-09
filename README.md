[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) [![Discord Banner](https://discord.com/api/guilds/1479794793394737152/widget.png)](https://discord.gg/fhwfqZzEJf)
[![Reddit](https://img.shields.io/reddit/subreddit-subscribers/obsidianalternative?style=social&logo=reddit)](https://www.reddit.com/r/ObsidianAlternative)

# 📂 List of active FOSS Obsidian Clones

## Tier 1 (fully Obsidian-compatible)
To be listed here, the FOSS Obsidian clone must work with the Obsidian vault format **without requiring a custom importer or conversion step**. This means same **Markdown[^0]** and **JSON Canvas[^1]**, same **bidirectional link handling[^2]** and same **free folder structure** for notes and their attachments. **Other features[^3] are optional**.

[^0]: Obsidian-flavored Markdown. 
[^1]: Implementing JSON Canvas as storage format must at least be present on the roadmap.
[^2]: Both wililinks with short path and long path must be understood and updated after renaming operations.
[^3]: Optional features include cross-platform support, built-in P2P sync, and specialized views (such as graph view or base view) that parse metadata from YAML frontmatter.

- **[Lokus](https://github.com/lokus-ai/lokus)** > cross-platform, canvas supported[^5], graph and base views supported
- **[Otterly](https://github.com/ajkdrag/otterly)** > cross-platform, canvas planned
- **[Cherit](https://github.com/Keshav-writes-code/Cherit)** > cross-platform, canvas planned
- **[Foam](https://github.com/foambubble/foam)** > VS Code plugin, not cross-platform

[^5]: Only Excalidraw format for now, but using JSON Canvas as storage format is on the roadmap.

## Tier 2 (opinionated)
Implementations listed here require an importer step for Obsidian vaults because they have **hard-coded the attachment folder** or they decided to **enforce long path** for the wikilinks. They are still required to have a free folder structure for notes and the same file formats as Obsidian.

- [**HelixNotes**](https://codeberg.org/ArkHost/HelixNotes) > cross-platform, UpNote-like UI

# 🚀 Tech Stack for Building Obsidian Clones
Essential tools for developers that want to make Obsidian clones a true commodity for the future, with their own clone.

## Filesystem
- **[Tauri](https://github.com/tauri-apps/tauri)**
- **[Notify](https://github.com/notify-rs/notify)**

## UI
- **[React](https://github.com/facebook/react)**
- **[Svelte](https://github.com/sveltejs/svelte)**

## Markdown
- **[Obsidian-Flavored Markdown spec](https://help.obsidian.md/obsidian-flavored-markdown)**
- **[CodeMirror](https://github.com/codemirror/dev)**  
- **[ProseMirror](https://github.com/ProseMirror/prosemirror)**
- **[reMark](https://github.com/remarkjs/remark)**

## Canvas
- **[JSON Canvas spec](https://github.com/obsidianmd/jsoncanvas)**
- **[Excalidraw](https://github.com/excalidraw/excalidraw)**  
- **[TLDraw](https://github.com/tldraw/tldraw)**
- **[React & Svelte Flow](https://github.com/xyflow/xyflow)**
- **[Throwdown JSON Canvas editor](https://github.com/staticeys/Throwdown)** (experimental)
- **[Open Canvas Interchange Format sync tools](https://github.com/ocwg)**


# 🌎 Community

This ecosystem is built for anyone interested in **FOSS alternatives compatible with the Obsidian vault format**. There are three channels to get involved:

- **[Discord](https://discord.gg/fhwfqZzEJf)** – Chat with developers and other users about the future of the ecosystem on our server.
- **[r/ObsidianAlternative](https://www.reddit.com/r/ObsidianAlternative/)** - Follow the latest updates and ask questions about the mentioned projects on our subreddit.
- **[Github](https://github.com/slimhk45/awesome-obsidian-alternatives/issues)** – Know of a project we missed or want to improve this list? You can open an issue.

We encourage **FOSS enthusiasts, PKM users, and developers** to join and help grow this ecosystem!

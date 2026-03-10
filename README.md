[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) [![Discord Banner](https://discord.com/api/guilds/1479794793394737152/widget.png)](https://discord.gg/fhwfqZzEJf)
[![Reddit](https://img.shields.io/reddit/subreddit-subscribers/obsidianalternative?style=social&logo=reddit)](https://www.reddit.com/r/ObsidianAlternative)


# 📂 List of active FOSS Obsidian Clones

## Tier 1 (fully Obsidian-compatible)
To be listed here, the FOSS Obsidian clone must work with the Obsidian vault format **without requiring a custom importer**. This means same **Markdown[^0]** and **JSON Canvas[^1]**, same **bidirectional link handling[^2]** and same **free folder structure** for notes and their attachments. **Other features[^3] are optional**.

[^0]: Obsidian-flavored Markdown. 
[^1]: Implementing JSON Canvas as storage format must at least be present on the roadmap.
[^2]: Both wililinks with short path and long path must be understood and updated after renaming operations.
[^3]: Optional features include cross-platform support, built-in P2P sync, and specialized views (such as graph view or base view) that parse metadata from YAML frontmatter.

- **[Lokus](https://github.com/lokus-ai/lokus)** → cross-platform, canvas supported[^5], graph and base views supported
- **[Otterly](https://github.com/ajkdrag/otterly)** → cross-platform, canvas planned
- **[Cherit](https://github.com/Keshav-writes-code/Cherit)** → cross-platform, canvas planned
- **[Mdit](https://github.com/hjinco/mdit)** → macOS-optimized, canvas and base planned
- **[Foam](https://github.com/foambubble/foam)** → VS Code plugin, not cross-platform

[^5]: Only Excalidraw format for now, but using JSON Canvas as storage format is on the roadmap.

## Tier 2 (opinionated)
Implementations listed here require an importer step for Obsidian vaults due to having a **hard-coded attachment folder** or enforcing **long paths for wikilinks**. While canvas support is not mandatory for listing here, a free folder structure for markdown notes is still essential.

- [**HelixNotes**](https://codeberg.org/ArkHost/HelixNotes) → cross-platform, UpNote-like UI


# 🚀 Tech Stack for Building Obsidian Clones
Essential tools for developers that want to make Obsidian clones a true commodity for the future, with their own clone.

## Framework/Filesystem
- **[Tauri](https://github.com/tauri-apps/tauri)**
- **[Notify](https://github.com/notify-rs/notify)**

## UI
- **[React](https://github.com/facebook/react)**
- **[Svelte](https://github.com/sveltejs/svelte)**

## Markdown
- **[Obsidian-Flavored Markdown spec](https://help.obsidian.md/obsidian-flavored-markdown)**
- **[reMark](https://github.com/remarkjs/remark)**
- **[CodeMirror](https://github.com/codemirror/dev)**  
- **[ProseMirror](https://github.com/ProseMirror/prosemirror)**

## Canvas
- **[JSON Canvas spec](https://github.com/obsidianmd/jsoncanvas)**
- **[Open Canvas Interchange Format tools](https://github.com/ocwg)** (see this [issue](https://github.com/lokus-ai/lokus/issues/433))
- **[Excalidraw](https://github.com/excalidraw/excalidraw)**  
- **[TLDraw](https://github.com/tldraw/tldraw)**
- **[React Flow | Svelte Flow](https://github.com/xyflow/xyflow)**
- **[Throwdown JSON Canvas editor](https://github.com/staticeys/Throwdown)** (experimental)


# 🌎 Community

This ecosystem is built for anyone interested in **FOSS alternatives compatible with the Obsidian vault format**. There are three channels to get involved:

- **[Discord](https://discord.gg/fhwfqZzEJf)** → Chat with developers and other users about the future of the ecosystem on our server.
- **[r/ObsidianAlternative](https://www.reddit.com/r/ObsidianAlternative/)** → Follow the latest updates and ask questions about the mentioned projects on our subreddit.
- **[Github](https://github.com/slimhk45/awesome-obsidian-alternatives/issues)** → Know of a project we missed or want to improve this list? You can open an issue.

We encourage **FOSS enthusiasts, PKM users, and developers** to join and help grow this ecosystem!

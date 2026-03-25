**Flatten for LLM** is a seamless, Godot plugin designed to bridge the gap between your game project and Large Language Models (LLMs).

When asking an AI for help with complex game logic or refactoring, pasting individual scripts often misses the bigger picture of how your scenes and resources connect. This plugin solves that by recursively crawling your project and compiling everything into a single, beautifully formatted Markdown document. The resulting file mimics your exact folder structure using Markdown headings, giving the LLM perfect structural awareness of your entire codebase.

## Features:
- **Native Editor Integration**: Runs directly in the Godot editor, docking natively next to your FileSystem tab for a frictionless workflow.
- **Smart Folder Filtering**: Easily specify exact folders to **Include Only** (perfect for scanning a single complex Addon) or folders to **Exclude** (like hiding standard `.godot` or `addons` directories).
- **Multi-Format Support**: Selectively export `.gd` (GDScript), `.tscn` (Scenes), `.tres` (Resources), and `.gdshader` (Shaders). Code blocks are automatically tagged with the correct syntax highlighting identifiers for the LLM.
- **Persistent Settings**: Your export paths and folder filters are saved automatically to your local `.godot` folder, keeping your configuration intact without cluttering your version control system.
- **Optimized Parsing**: Generates structural Markdown headings corresponding to your project's tree, allowing the LLM to understand not just your code, but your project's architectural hierarchy.

Stop manually copying and pasting scripts one by one. Use Flatten for LLM to inject your entire game's context into your favorite AI assistant in seconds.

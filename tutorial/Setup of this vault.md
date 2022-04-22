You can download this vault from: https://github.com/argenos/obsidian-tutorial-researcher

## Plugins

I enabled the following core plugins:

- daily note - create notes based on a date and template
- backlinks - Showing notes that link back to or mention the currently open note
	- Also enabled "backlinks in document" setting so they show up at the bottom of all notes
- templates - Apply templates at your cursor position (you can add a hotkey for this)
- outgoing links - See links present on this note and other notes you could link based on contents
- tag pane - see all the tags being used in all the notes contained in your notes folder (e.g. #tutorial)
- slash commands - type <kbd>/</kbd> to open the command palette (which you can also open with the default hotkey <kbd>ctrl</kbd> + <kbd>P</kbd>)
- starred - add "favourite" files
- outline - shows the outline of the current note based on headers and can be used to navigate
- slides - basic functionality using reveal.js


I've set up this vault to include some third-party plugins that help with more advanced stuff in some common use cases:

- [outliner](obsidian://show-plugin?id=obsidian-outliner) - better outliner behaviour when using lists
- [natural language dates](obsidian://show-plugin?id=nldates-obsidian) - creating date-based notes using natural language, e.g. by typing `@today` or `@next friday`
- [calendar](obsidian://show-plugin?id=calendar) - Nice GUI to open daily notes
- [periodic notes](obsidian://show-plugin?id=periodic-notes) - Better functionality for daily notes and support for more types of date-based notes, e.g. weekly notes for planning if you follow GTD
- [quick add](obsidian://show-plugin?id=quickadd) - Useful to add slash commands to automate creating notes and applying templates, e.g. `/meeting` 
	- I've set up one example for the [[Death Star]] project which essentially 
		- creates a new file for a specific date following a naming convention
		- saves the new file in the `projects/death star/meetings` folder
		- applies a template for the meeting notes
		- opens the file to the right of the current note you're working on
		- and adds a link to this new note in the current file
	- there's a lot of options to customize or remove any of the previous steps
- Slides - The core plugin gives basic slides, but a plugin adds more versatility: [Advanced slides](obsidian://show-plugin?id=obsidian-advanced-slides)
	- Example: [[Slides]]
- Jupyter notebooks: [Jupyter](obsidian://show-plugin?id=obsidian-jupyter)
	- Example: [[Jupyter example]]
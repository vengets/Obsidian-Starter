# Obsidian-Starter
Open it as a vault with Obsidian, having all the templates and necessary plugins to kick start your knowledge base.

Cmd + P for command palette.

# Plugins

### Admonition

Used for creating tips

```ad-tip
title: How to use admonition
Start with 3 backticks [`] followed by ad-tip.
Next line "title:" with title message.
Last line is for description of the tip
Close the segment with 3 backticks [`]
```


###  Advanced Tables for Obsidian

Used for creating tables, Use cmd+shift+d (mac) or ctrl+shift+d for table controls sidebar.

```ad-tip
title: How to create a table
 Start with | symbol.
 Input field names like  | first-name | last-name | 
 Table will be generated
```

| first-name | last-name   |
| ---------- | ----------- |
| Venkatesh  | Kamalapathy |

### Obsidian Dataview

Treat your [Obsidian Vault](https://obsidian.md/) as a database which you can query from. Provides a JavaScript API and  
pipeline-based query language for filtering, sorting, and extracting data from Markdown pages.

See the Examples section  
below for some quick examples, or the full [reference](https://blacksmithgu.github.io/obsidian-dataview/) for all the details.

```ad-tip
title: How to use dataview?
Start with 3 backticks [ ` ] and "dataview" 
Next line onwards we can write our query.
End the segment with 3 backticks [ ` ].
```

### Templater

[Templater](https://github.com/SilentVoid13/Templater) is a template plugin for [Obsidian.md](https://obsidian.md/). It defines a templating language that lets you insert variables and functions results into your notes. It will also let you execute JavaScript code manipulating those variables and functions.

A list of useful resources about [Templater](https://github.com/SilentVoid13/Templater)

### Outliner

Move lists with children wherever you want without breaking the structure.

```ad-tip
title: How to use outliner
Here are the shortcuts
Cmd/ctrl + shift + arrowkey
tab
shift + tab
```

- Apple
- Banana
	- Bat
	- Ball
	- Bike
- Carrot
	- car
	- clip
- Drumstick
	- Drum
	- Doll

### Excalidraw

You can store and edit Excalidraw files in your vault, you can embed drawings into your documents, and you can link to documents and other drawings to/and from Excalidraw.


### Editor Syntax Highlight

 It allows syntax highlighting for code blocks in the editor.
```javascript
function displayHi() {
	console.log('Hi');
}
```

### Checklist

 Run the `Checklist: Open View` command from the command palette to get it to appear.

```ad-tip
title: How to add a checklist?
You can create a checklist by "- [ ] -> name"
And finish it by adding "x" inside it.
Example: "[x] -> name"

```

- [x] #todo checklist sample item

### Paste URL into selection

Insert links (URLs) into a selected text "notion-style" using regular `Ctrl/Cmd + V`

```ad-tip
title: How to paste url into selected text?
Simply paste it after selecting a text you wanted to make it hyperlink.
```

### Obsidian MarkMind

Obsidian MarkMind is a mind map, outline, and PDF annotate tool based on Obsidian API.

### Tasks
Similar to checklist but with option to specify deadline, repeat and icons.

Ex: 
- [ ] 📅 2023-07-07 🛫 2023-07-07 🔺 🔁 every day  Sample item


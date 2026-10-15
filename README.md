# paper-to-bullets-skills

A Claude Code plugin marketplace with one plugin, **paper-to-bullets**. It turns a research paper into five bullets:

- **Title:** the paper's title
- **Question:** the research question it asks
- **Method:** how it answers that question
- **Result:** the main finding
- **Limitation:** the most important limitation

## Install

In Claude Code, add the marketplace, then install the plugin.

From GitHub:

```
/plugin marketplace add roivigo98/paper-to-bullets-skills
/plugin install paper-to-bullets@paper-to-bullets-skills
```

From a local copy of this folder:

```
/plugin marketplace add ./paper-to-bullets-skills
/plugin install paper-to-bullets@paper-to-bullets-skills
```

Restart Claude Code if the skill doesn't show up right away.

## Use

Share a paper and ask Claude to triage it, or run the skill directly:

```
/paper-to-bullets path/to/paper.pdf
```

## Layout

```
paper-to-bullets-skills/
├── .claude-plugin/
│   ├── marketplace.json   # marketplace listing; source "./"
│   └── plugin.json        # plugin manifest
├── skills/
│   └── paper-to-bullets/
│       └── SKILL.md
└── README.md
```

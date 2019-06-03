A light-weighted Angular Development Tool for Eclipse including:
1. TypeScript and Angular Micro Syntax Language syntax parser generated from grammar files written in ANTLR
2. A TypeScript Editor that supports real-time syntax parsing and coloring, code folding/expanding, auto completion proposals, hyperlink and navigation, syntax and semantic problem detecting and quick fix proposal, element renaming, source code formatting
3. Extensions to Eclipse WTP html editor for Angular templates editing - auto completion proposals, hyperlink and navigation, syntax and semantic problem detecting
4. A View to show all references of element selected in TypeScript Editor
5. TypeScript code structure Outline Page
6. Internal model manager to maintain integrity of TypeScript and Angular model, dependencies and relations between elements and modules
Installation requirements:
1.	Eclipse Version and installed Plugins
Eclipse version should not matter but must be installed with JDT (Eclipse Java development tools) and Eclipse WTP (Web Tool Platform) Plugins
2.	Memory
It’s strongly recommended that “-Xmx” option in “eclipse.ini” file is configured to no less than 1536 M:
…
-Xmx1536m
…

## Cursor on Mac OS

### Remove the sticky keys

```
defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false
```

```
defaults write -g ApplePressAndHoldEnabled -bool false
```

### Editor Defaults


```
{
    "workbench.colorTheme": "Light 2026",
    "workbench.activityBar.location": "top",  // moves activity bar out of the way
    "claudeCode.preferredLocation": "panel",
    "editor.fontFamily": "'JetBrains Mono', 'Fira Code', 'Cascadia Code', Menlo, Monaco, 'Courier New', monospace",
    "editor.fontSize": 14,  // or 15-16 for more comfort
    "editor.lineHeight": 22,  // adds breathing room between lines
    "editor.fontLigatures": true,  // enables ligatures if your font supports them
    "editor.smoothScrolling": true,
    "editor.cursorBlinking": "smooth",
    "editor.cursorSmoothCaretAnimation": "on",
    "terminal.integrated.fontSize": 13,
    "editor.minimap.enabled": false,  // removes minimap if you don't use it
    "editor.renderWhitespace": "selection",  // only shows whitespace when selected
    "breadcrumbs.enabled": true,  // helpful for navigation
}
```


# knowledge
Unsorted and uncategorized knowledge from my daily work

## regex

### Search value of href and take it for the attribute download

search

    href="([^"]*)"

replace

    href="$1" download="$1"

## Sublime Text

### keyboard shortcut to comment lines

Preferences->Key Bindings - User

    { "keys": ["ctrl+7"], "command": "toggle_comment", "args": { "block": false } },
    { "keys": ["ctrl+shift+7"], "command": "toggle_comment", "args": { "block": true } }



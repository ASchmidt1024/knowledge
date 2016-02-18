# knowledge
Unsorted and uncategorized knowledge from my daily work

## css

### text fade out of last line

    .selector {
		position: relative;
		line-height: 1.7;
		height: 3.4em; // height of two lines
		&:after {
			content: "";
			text-align: right;
			position: absolute;
			bottom: 0;
			right: 0;
			width: 70%;
			height: 1.7em; // height of line-height
			background: linear-gradient(to right, rgba(255, 255, 255, 0), rgba(255, 255, 255, 1) 50%);
		}
    }

## regex	// fade out
		position: relative;
		height: 3.4em;
		&:after {
			content: "";
			text-align: right;
			position: absolute;
			bottom: 0;
			right: 0;
			width: 70%;
			height: 1.7em;
			background: linear-gradient(to right, rgba(255, 255, 255, 0), rgba(255, 255, 255, 1) 50%);
		}

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



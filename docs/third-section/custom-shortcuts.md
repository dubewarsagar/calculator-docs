# Custom Keyboard Shortcuts

> [!NOTE]
> The calculator allows users to define custom shortcuts for quick calculations.

## Creating a Shortcut
Shortcuts are stored in the `shortcuts.json` file.

### Example Shortcut Configuration:
```json
{
  "shortcut": "ctrl+alt+a",
  "command": "add",
  "arguments": [5, 3]
}
```

- `"shortcut"`: Key combination.
- `"command"`: Operation (e.g., `add`, `multiply`).
- `"arguments"`: Default numbers for the operation.

## Using Shortcuts
Once set up, press `Ctrl + Alt + A` to automatically perform:
```sh
calculator.exe add 5 3
# Output: 8
```

## Next Steps
To learn about exporting and importing calculations, see [Exporting & Importing Data](export-import.md).
```
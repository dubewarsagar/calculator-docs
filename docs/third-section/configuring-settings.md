# Configuring Calculator Settings

> [!TIP]
> The calculator allows customization through a configuration file.

## Modifying the Configuration File
Users can change calculator settings by editing the `config.json` file.

### Example Configuration:
```json
{
  "precision": 4,
  "theme": "dark",
  "history_enabled": true
}
```

- `"precision"`: Number of decimal places in results.
- `"theme"`: `"light"` or `"dark"` mode.
- `"history_enabled"`: Enables or disables history tracking.

## Applying Changes
After modifying `config.json`, restart the calculator:
```sh
calculator.exe --reload-config
```

## Next Steps
To set up custom shortcuts, see [Custom Keyboard Shortcuts](custom-shortcuts.md).
```
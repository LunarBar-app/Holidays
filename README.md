# Holidays

Online database of public holidays used in LunarBar.

## Example

Here's an example to explain the public holiday format:

```json
{
  "2024": {
    "0101": 2,
    "0204": 1
  }
}
```

It means that `2024/1/1` is a holiday (2), and `2024/2/4` is a workday (1), month and day should always be formatted as four digits.

Open the `Holidays` directory in the app, put the definition file (must be `*.json`) there and select `Reload Customizations`.

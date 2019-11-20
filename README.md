# Sanity Color Picker

Display colors for editors to choose from with this custom input component.

![preview image](https://github.com/KimPaow/sanity-color-picker/raw/master/src/images/preview.png)

## Installation

1. `sanity install color-list`
2. In your schema:

```
...,
{
  title: "Color Picker",
  name: "colorpicker",
  type: "colors",
  options: {
    list: [
      { title: "Yellow", value: "#f5c701" },
      { title: "Pink", value: "#f6cedb" },
      { title: "Red", value: "#f16d70" },
      { title: "Teal", value: "#88c6db" },
      { title: "Purple", value: "#aca0cc" },
      { title: "Green", value: "#bdcdcb" },
      { title: "White", value: "#fff" }
    ]
  }
},
...
```

Profit. The component returns the selected value.
# river-themes
Themes for River

## Documentation

> Note: You need to set the `uuid` correctly, if you leave the same uuid, it will mess the theme or may appear incorrect theme option 

> You can use this example when you want to create your own themes

### Example: `theme-name.json`

```json
{
	"uuid": 1,
	"name": "",
	"mode": "",
	"primary": "",
	"secondary": "",
	"success": "",
	"warning": "",
	"error": "",
	"info": "",
	"divider": "",
	"background": {
		"default": "",
		"paper": ""
	},
	"text": {
		"primary": "",
		"secondary": "",
		"disabled": ""
	}
}
```

## `uuid`
Provide the uuid of a theme

### Example
```json
{
	"uuid": 1
}
```

## `Name`
Provide the theme's name

### Example
```json
{
	"name": "Pastel Blue"
}
```


## `mode`
You must type `"light"` or `"dark"`

Using `"light"` will use light color and `"dark"` also uses dark color too

> Select what you prefers, no doubt what you like

### Example

#### Light mode
```json
{
	"mode": "light"
}
```

#### Dark mode
```json
{
	"mode": "dark"
}
```

## `"primary"`,`"secondary"` and other more
> Primary and Secondary is with `#hex-code`

It provides coloring at some components that uses `primary` like `<AppBar />` or the `<Button />`, etc.

> Also `"success"`, `"info"` and other can be applied with `#hex-code`

### Example
```json
{
	"primary": "#4ec9ff",
	"secondary": "#23bcff",
	"success": "#b7ffb9",
	"warning": "#fffbb7"
}
```

## `"background"`
Contains `"default"` and `"paper"`

> You must add `#hex-code` in order to change the background

### `"default"`
Provides the background color 

> Note: Changing the background color will cause contrast issue if you don't, please check at `text` color before you change the background to match correctly

#### Example
```json
{
	"background": {
		"default": "#cef0ff",
	}
}
```

### `"paper"`
Provides the paper color like `<Menu />`, `<Card />` and other more

#### Example
```json
{
	"background": {
		"paper": "#b1e7ff",
	}
}
```

## `"text"`
Provides the text colors

Contains `"primary"`, `"secondary"` and `"disabled"`

> You must type the `#hex-color` too 

### `"primary"`

> Affects almost all the texts unless any components (like `<Button />`) that uses `inherit`

This is a primary text color, they uses it own color as `@mui/material` uses

#### Example
```json
{
	"text": {
		"primary": "#000000",
	}
}
```

### `"secondary"`

> I don't know why this exist but... I don't see any secondary text :/

#### Example
```json
{
	"text": {
		"secondary": "#363636",
	}
}
```

### `"disabled"`

This color uses for when a button or component is disabled

#### Example
```json
{
	"text": {
		"disabled": "#727272",
	}
}
```



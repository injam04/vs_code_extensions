# VS Code Extensions
All of my vs code extensions &amp; setup method

## Basic Things:
### 1. Prettier - Code formatter
Goto settings and type "format on save" and search. Then, tick on "format on save".
<br>
Goto settings.json and paste this
````
"prettier.jsxSingleQuote": true,
"prettier.singleQuote": true
````

### 2. Auto Rename Tag

### 3. Color Highlight

### 4. Live Server

### 5. Lorem ipsum

### 6. vscode-icons

### 7. Bracket Pair Colorizer

## Themes:
### 1. SynthWave '84
Goto settings.json and paste this
```` "synthwave84.brightness": "0.75" ````

### 2. Shades of Purple

### 3. Night Owl

### 4. Palenight Theme

### 5. Vue Theme

### 6. Cobalt2 Theme Official

### 7. Dracula Official

### 8. Change Font (Operator Mono)
Goto settings.json and paste this
```` 
"editor.fontFamily": "Operator Mono",
"editor.fontLigatures": true,
"editor.fontWeight": "300",
````

## For PHP:
### 1. phpfmt - PHP formatter
Goto settings.json and paste this
````
"phpfmt.psr2": false,
"phpfmt.passes": [
  "AlignDoubleArrow",
  "SpaceAroundParentheses"
],
````

### 2. Beautify Blade
Goto settings and type "blade" and search. Then, tick on "Enabal format blade file".

### 3. PHP Namespace Resolver

### 4. Laravel Blade Snippets

### 5. Laravel Snippets

### 6. PHP Intelephense

## For Vue.js:

### 1. Vetur

### 2. Vue VSCode Snippets

### 3. vue
Syntax Highlight for Vue.js

### 4. ESLint

## For Bootstrap:
### 1. Bootstrap 4, Font awesome 4, Font Awesome 5 Free & Pro snippets for Visual studio code

## Others:
### 1. jQuery Code Snippets

### 2. Live Sass Compiler

# User Snippets
## For PHP:
````
"laravel": {
	"prefix": "pfunction",
	"body": [
		"public function $1()",
		"{",
		"	",
		"}",
	],
	"description": "public function laravel."
}
````
````
"laravel2": {
	"prefix": "returnview",
	"body": [
		"return view('$1');",
	],
	"description": "return view laravel."
}
````

## For Blade:
````
"print": {
	"prefix": "print",
	"body": [
		"{{ $1 }}",
	],
	"description": "print value in blade file."
}
````

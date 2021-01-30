# dirtcheapcss 👨🏼‍💻

## About

I needed something to quickly stylize a simple HTML page into a readable document that looked mostly good on all devices. It weighs in at 375b and that's without any code minification. This is clearly not meant for every solution, but in a pinch it can turn an ugly blog or documentation into a decent thing to look at.

## How to use

The easiest approach is to append the inline style to your `<head>` section of your HTML document.

### HTML inline

```html
<style> html { color-scheme: light dark; color: #333; font: 300 2.2ch/1.5 ui-sans-serif, sans-serif; max-width: 70ch; padding: 1ch; margin: auto; } h2,h3,h4,h5,h6 { margin-top: 3ch; } code,pre { font: 1.4ch ui-monospace, fixed; opacity: 0.7; overflow-x: auto; } img { max-width: 100%; } @media (prefers-color-scheme: dark) { html,a:link { color: #ddd; } a:visited { color: #999; } } </style>
```

## Example
[https://peterrother.com/dirtcheapcss](https://peterrother.com/dirtcheapcss/)

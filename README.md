# MVP.css — Minimalist stylesheet for HTML elements

![MVP.css](img/logo.png)

Out of the box CSS styling for HTML elements. No class names, no framework to learn.

Live demo: <https://andybrewer.github.io/mvp/>

Unpkg: <https://unpkg.com/mvp.css>

NPM: <https://www.npmjs.com/package/mvp.css>

## Versions

### v1.16

* Removed a deadlink from the README.md
* Add missing comma to restore textarea width
* Add styles for dialog element & its backdrop

### v1.15

* Add `text-wrap: balance`
* Only apply top border radii on first table header row
* fix(scrollbar): use transparent as track color
* feat(scrollbar): adjustable color using variable

### v1.14

* Added smooth scrolling by default

### v1.13

* Styled `<a>` element to be underlined by default
* Styled scrollbar to be in-line with MVP styling

### v1.12

* Styled `<input type="submit">` element to be the same as `<button>`

### v1.11

* Styled `<dialog>` element

### v1.10.2

* Updated `<input type="text">` and `<textarea>` styling to be full-width elements

### v1.9

* Updated `<input type="range">` styling to allow user to select all numerical values
* Added the option to handle a user's dark mode preference by using `<html color-mode="user">`

### v1.8

* Updated `<p>` to be full width
* Added `--color-link` and `--color-table` variables
* Added `--active-brightness` variable plus `a:active` and `button:active` styles
* Uncommented dark mode

### v1.7

* Updated `<a>` to use `--color` (primary color)
* Updated `<section>` to handle overflow content
* Updated `<section><img>` and `<article><img>` to with within their containers by default
* Added a showcase section to README

### v1.6

* Added `[hidden]` styling to hide hidden elements
* Updated alternate table rows to use `--color-accent` for a more branded look
* Updated `<table>` to use `display: block` and removed `overflow` styling
* Updated `font` variable to `font-family`
* Updated `<pre>`, `<code>` and `<samp>` styling to have proper padding and recognize indented content
* Updated `line-height` to be a number instead of a percentage
* Updated multi-word dropdown menu titles to render on a single line

### v1.5

* Added browser default `:focus` styling back in for better tabbed navigation
* Updated `<a>` styling to use `display: inline-block` for better focus outlines on buttons
* Added `<label>` styling for `checkbox` and `radio` elements
* Added striped `<table>`

### v1.4

* Updated `<pre>` styling to use `pre-line` for better line breaks
* Added hover styling to `<details><summary>` tags

### v1.3

* Updated `<button>` `line-height` and `font` to match `<a><b>` button styles
* Added a `--font` variable
* Added dropdown menus

### v1.2

* Added `checkbox` and `radio` styling for `<input>` fields
* Added `disabled` and `readonly` styling

### v1.1

* Updated code blocks to use `<pre><code>` instead of `<samp>`
* Added light styling for `<select>` fields
* Added `<details>` and `<summary>` tags
* Added `prefers-color-scheme: dark` media query (commented out by default)
* Updated `<table>` styling

## Contributors

* [andybrewer](https://github.com/andybrewer)
* [aembleton](https://github.com/aembleton)
* [afeld](https://github.com/afeld)
* [cfv1984](https://github.com/cfv1984)
* [coolaj86](https://github.com/coolaj86)
* [ctp52](https://github.com/ctp52)
* [DiemenDesign](https://github.com/DiemenDesign)
* [edlinkiii](https://github.com/edlinkiii)
* [ericwbailey](https://github.com/ericwbailey)
* [GrosSacASac](https://github.com/GrosSacASac)
* [hongsw](https://github.com/hongsw)
* [irfaardy](https://github.com/irfaardy)
* [martin-v](https://github.com/martin-v)
* [michaelp-coder](https://github.com/michaelp-coder)
* [nikolai-cc](https://github.com/nikolai-cc)
* [ruudud](https://github.com/ruudud)
* [ScottGuthart](https://github.com/ScottGuthart)
* [simonw](https://github.com/simonw)
* [thedamon](https://github.com/thedamon)

## Showcase

* <https://bliss.js.org/>
* <https://chrisbilger.com/>
* <https://figmage.com/>
* <https://www.mondage.com>
* <http://nextvita.vercel.app/>
* <https://searchcode.com/>
* <https://stadtfuehrung.stadtroda.de/>

To submit your site built with MVP.css create a pull request or an issue. For pull requests, please keep sites in alphabetical order.

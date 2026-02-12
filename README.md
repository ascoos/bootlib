![BootLib](https://cdn.ascoos.com/images/bootlib/bootlib-logo.png)

---

# BootLib UI Framework

### For the Greek version, see [README-GR.md](README-GR.md).

---

[![Ascoos Bootlib Framework - state of Official Website](https://img.shields.io/website?url=https://bootlib.ascoos.com&style=for-the-badge&labelColor=%234e555b&color=006400)](https://bootlib.ascoos.com) 
[![License AGL-F](https://img.shields.io/badge/AGL--F-blue?style=for-the-badge&label=LICENSE&labelColor=%234e555b&color=873260)](https://github.com/ascoos/bootlib/blob/main/LICENSE_AGL-F.md)
[![BootLib is Under Developement](https://img.shields.io/badge/1.0.0%20alpha%207-blue?style=for-the-badge&label=DEVELOPMENT%20EDITION&labelColor=041f60&color=034f84)](https://bootlib.ascoos.com)

***

<details>
<summary>
  🟠 General informations
</summary>
<br>

![Ascoos Bootlib Framework - Forks](https://img.shields.io/github/forks/ascoos/bootlib)
![Ascoos Bootlib Framework - Stars](https://img.shields.io/github/stars/ascoos/bootlib)
![Ascoos Bootlib Framework - Watchers](https://img.shields.io/github/watchers/ascoos/bootlib)
</details>

<details>
<summary>
  🟠 Repository and Releases
</summary>
<br>

[![Ascoos Bootlib Framework - Release](https://img.shields.io/github/v/release/ascoos/bootlib)](https://github.com/ascoos/bootlib/releases)
![Ascoos Bootlib Framework - Release Date](https://img.shields.io/github/release-date/ascoos/bootlib?color=%230E80C0)
![Ascoos Bootlib Framework - Downloads (all assets, all releases)](https://img.shields.io/github/downloads/ascoos/bootlib/total?color=%230E80C0) 
[![Ascoos Bootlib Framework - latest release tag](https://img.shields.io/github/tag/ascoos/bootlib.svg)](https://github.com/ascoos/bootlib/tags)
![Ascoos Bootlib Framework - repo size](https://img.shields.io/github/repo-size/ascoos/bootlib)

</details>

<details>
<summary>
  🟠 Issues - Requests
</summary>
<br>

[![Ascoos Bootlib Framework - Open Issues](https://img.shields.io/github/issues/ascoos/bootlib)](https://github.com/ascoos/bootlib/issues)
[![Ascoos Bootlib Framework - Closed Issues](https://img.shields.io/github/issues-closed/ascoos/bootlib)](https://github.com/ascoos/bootlib/issues)
[![Ascoos Bootlib Framework - Open Pull Requests](https://img.shields.io/github/issues-pr/ascoos/bootlib)](https://github.com/ascoos/bootlib/pulls)
[![Ascoos Bootlib Framework - Closed Pull Requests](https://img.shields.io/github/issues-pr-closed/ascoos/bootlib)](https://github.com/ascoos/bootlib/pulls)
![Ascoos Bootlib Framework - Last Commit](https://img.shields.io/github/last-commit/ascoos/bootlib)
</details>

<details>
<summary>
  🟠 Quick Links
</summary><br>

- [Official Website](https://bootlib.ascoos.com)
- [Flex Examples](https://bootlib.ascoos.com/examples/flex/)
- [Ascoos OS](https://os.ascoos.com)
</details>

---

## Table of Contents
- [What is the BootLib Framework?](#what-is-the-bootlib-framework)
- [Why Choose BootLib?](#why-choose-bootlib)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Usage Example](#usage-example)
- [Abbreviations](#abbreviations)
- [Themes](#themes)
- [Helper Applications](#helper-applications)
- [Online Examples](#online-examples)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## What is the BootLib Framework?

BootLib (Boot Library) is a Frontend/Backend CSS, jQuery, and PHP framework aimed at facilitating developers in creating their projects.

It consists of a variety of components that are typically essential for completing a website.

The implementation of its components is usually done through the CSS3 UI Creator code, but there are components implemented via the jQuery `BootLib` class.

This framework will be one of the core components of the new [Ascoos OS](https://os.ascoos.com) and, by extension, the new `Ascoos Oxyzen`.

---

## Why Choose BootLib?

`BootLib`, unlike other frameworks, is focused (like all `Ascoos` products) on appearance themes. This means that for each component, there is a wide range of alternative appearances.

This is not left solely to the user. With its extensive range of themes, which in some elements exceeds 500 styling classes, it empowers both the website creator and `the end user` to validly and quickly customize the various components of their website.

The optional use of framework extensions makes it modular and flexible. For example, the use of `background patterns` is included in an extension file and does not burden the main framework file.

In summary, some reasons to choose BootLib:

- **CSS3 Simplicity**: Easy to learn and use.
- **jQuery/jAscoos Flexibility**: Ideal for dynamic applications.
- **Rich Themes**: Over 500 classes for each element.
- **Lightweight**: Fast and without unnecessary bloat.

---

> ‼️ Note
> ---
> This text is dynamic and not fully completed because **`BootLib`** is still in the development process.

---

## Installation

To use BootLib, you need to include one (or two, if you want to use extended libraries such as patterns) link in the `head` of your HTML file.

> ‼️ Note
> ---
> For now, only the initial test libraries are available, as the framework is being expanded and improved almost daily until its final form.

```html
   <link rel="stylesheet" href="https://cdn.ascoos.com/bootlib/css/bootlib.min.css">
   <link rel="stylesheet" href="https://cdn.ascoos.com/bootlib/css/bootlib.ext.min.css">
```

To use the extended features with the BootLib Javascript Library (`Bojali` -- in Albanian, the word means anchorage... full of meaning for `BootLib`), you need to load the JavaScript file, which is not currently available. 

The JavaScript file will be available in an upcoming release.

```html

<script type="javascript" src="https://cdn.ascoos.com/bootlib/js/bootlib.min.js"></script>

```

### Quick Start
Transform an anchor into a button with a motion effect in seconds:
```html
<link rel="stylesheet" href="https://cdn.ascoos.com/bootlib/css/bootlib.min.css">
<link rel="stylesheet" href="https://cdn.ascoos.com/bootlib/css/bootlib.ext.min.css">

<a class="blib-btn blib-btn-outline-primary blib-e-ani-bounce-glow" href="#">Click here!</a>

```

---

## Usage Example

The following complete example demonstrates the use of BootLib classes on various elements.

The use of different effects shows that BootLib can create nearly infinite combinations.

The ability to assign a class to an element originally designed for another purpose enables the creation of unique visual elements.

In the following example (which you can view online at [Flex Examples](https://bootlib.ascoos.com/examples/flex/)), ready-made effects are used, such as:

- `blib-e-ani-pop`: Creates a quick zoom effect, giving the illusion of an explosion.
- `blib-e-ani-fade-in`: Creates the sensation that the element is coming from the background.
- `blib-e-ani-bounce-glow`: Bouncing with simultaneous brightness change.
- `blib-e-hov-gradient`: Creates an element with a gradient background color that changes colors when hovered over.

```html
<!DOCTYPE html>
<html lang="en">
<head>
<title>BootLib Flex: Basic Horizontal Layout with Effects</title>
<meta charset="utf-8" />
<meta name="description" content="Creates a horizontal layout with three elements and effects." />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<link rel="stylesheet" href="https://cdn.ascoos.com/bootlib/css/bootlib.min.css">
<link rel="stylesheet" href="https://cdn.ascoos.com/bootlib/css/bootlib.ext.min.css">

<style>
    body {margin: 0; padding: 0;}
    a {margin-top: 10px; text-decoration: none;}
    .flex-items {color: white; padding: 1rem;}
    .blue {background-color: #0d6efd;}
    .green {background-color: #198754;}
    .red {background-color: #dc3545;}
</style>
</head>
<body class="blib-center-flex blib-flex-column">
    <h1 class="blib-h-heading-classic">BootLib Flex</h1>
    <div class="blib-h-box-clean-matte-finish-1">
        <h2 class="blib-h-heading-elegant">Basic Horizontal Layout with Effects</h2>
        <cite class="blib-h-cite-bg-color">Creates a horizontal layout with three elements and effects.</cite>
        <blockquote class="blib-h-blockquote-border-accent blib-e-ani-pop">blib-flex-row | blib-e-ani-fade-in | blib-e-ani-bounce-glow | blib-e-hov-gradient</blockquote>
        <hr class="blib-h-hr-bubble">
        <div class="blib-flex blib-flex-row">
            <div class="flex-items blue blib-e-ani-fade-in">Item 1</div>
            <div class="flex-items green blib-e-ani-bounce-glow">Item 2</div>
            <div class="flex-items red blib-e-hov-gradient">Item 3</div>
        </div>
    </div>
    <a class="blib-btn blib-btn-outline-primary" href="index.html">Back to the flex page</a>
</body>
</html>
```
---

## Abbreviations
To create a timeless structure that makes BootLib independent of other structures, BootLib follows certain standards in the naming of its classes and components.
Initially, every BootLib element starts with the prefix **`blib`**. This ensures no conflicts with other libraries and frameworks that could invalidate the formatting of its components.
Below is a table explaining each abbreviation in the naming convention.

### General Abbreviations

- `ani-` : Animation Effect.
    - Always followed by `e-`.
        - Example usage: `blib-e-ani-slide-in-001`.
- `blib-` : **`BootLib`**. Placed in front of everything to avoid conflicts with other frameworks.
- `c-` : Color.
    - Example usage: `--blib-c-red: red`.
- `bgc-` : Background Color.
    - Example usage: `--blib-bgc-gray-dark: #333`.
- `e-` : Effects.
    - Example usage: `blib-e-ani-*` or `blib-e-hov-*`.
- `ff-` : Font Family.
- `flex-` : Flex.
- `fs-` : Font Size.
- `grid-` : Grid.
- `h-` : HTML.
- `hov-` : Hover Effect.
    - Always followed by `e-`.
        - Example usage: `blib-e-hov-text-glow-001`.
- `kf-` : KeyFrames.
- `l-` : Layout.
- `p-` : Patterns.
    - Example usage: `blib-p-diagonal-stripes-001`.

### Example of a Pre-Built Effect:

```css
/* Slide In */
@keyframes blib-kf-slide-in {
    from {
        transform: translateX(-100%);
        opacity: 0;
    }
    to {
        transform: translateX(0);
        opacity: 1;
    }
}

/* blib-animate-slide-in */
.blib-e-ani-slide-in {
    animation: blib-kf-slide-in 0.5s ease-in-out forwards;
}
```

### HTML Abbreviations

HTML tags are implemented with their name, but following `blib-h-`.
For example, the styling of a paragraph takes the following form:

- `p-` : HTML Paragraph tag.
    - Always followed by `h-`.
        - Example usage: `blib-h-p-classic-001`.
- `blockquote` :. E.g., `blib-h-blockquote-shadow`.

---

## Themes
BootLib comes with hundreds of styling classes for each individual visual element, as well as complete themes for the appearance of the entire website.

For example, if you apply the `retro-terminal` theme to the `<body>`, all HTML elements will appear with the look of an old terminal (bright green on a black background). This, of course, assumes you haven’t applied any other styling class to an HTML element later.

```html
<body class="retro-terminal">
   .....
</body>
```

---

## Helper Applications

On the official `BootLib` website (which is under construction), there will be a variety of helper pages and applications to help you better utilize the framework.

Indicatively, I mention the following:

### 1. `Patterns Gallery`

`BootLib` includes a variety of ready-to-use patterns.

You can visualize them immediately through the `Patterns Gallery` application.

You can display and download the creation code directly and adapt it to your needs if the existing library doesn’t meet your requirements.

![Patterns Gallery](https://s.ascoos.com/images/bootlib/pub/screenshot-0014.png)

### 2. `Font Icons`

The framework includes an internal icon font with over **`2000 icons`**.
Font icons are implemented with the identifier `bfi` (BootLib Font Icon).

```html
   <button class="bfi-btn">
      <span class="bfi-wrapper"><i class="bfi bfi-twitter-1"></i></span>
      <span class="bfi-btn-text">bfi-twitter-1</span>
   </button>           
```

![Font Icons](https://s.ascoos.com/images/bootlib/pub/screenshot-0037.png)

---

### 3. `Effects and Animations`

`BootLib` includes a variety of effects and animations accompanied by a large keyframe library.

This allows you to combine static stylings or specially crafted effects with various other effect and motion classes, filters, and more.

The `Animation Playground` application will help you understand each effect, obtain the creation code, style it, and get your own code.

![Animation Playground](https://s.ascoos.com/images/bootlib/pub/scr-000002-1024.png)

---

## Online Examples

1. [Flex Examples](https://bootlib.ascoos.com/examples/flex/)

    This page contains examples of using BootLib Flex. Other classes are also used to style the remaining elements.
    
2. More example and test pages are coming soon.

---

## License
This project is licensed under the [AGL-F](https://github.com/ascoos/bootlib/blob/main/LICENSE_AGL-F.md) license. See the LICENSE file for details.

---

## Acknowledgments
BootLib is inspired by the need for faster and easier websites.

Let’s make BootLib the future of CSS Frameworks together! 🚀





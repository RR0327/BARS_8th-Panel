# Day-4 CSS Practice Task

## Task Title

Styled Profile and Product Card Page

---

## Objective

The objective of this task is to apply foundational CSS knowledge and understand how CSS styles and controls HTML elements.

By completing this task, students will practice:

- CSS syntax
- Selectors (element, class, id, universal)
- Internal and inline CSS
- CSS comments
- Common CSS errors
- Colors (named, hex, RGB, HSL)
- Background properties
- Border properties
- Margin and padding
- Height and width
- The CSS Box Model

The focus is on understanding structure, behavior, and correctness rather than advanced design.

---

# Project Overview

Create a simple webpage that contains:

- A profile section
- A product card section
- A basic form
- Clear spacing using margin and padding
- A visible demonstration of the Box Model

Use internal CSS inside the `<style>` tag.

---

# Requirements

---

## 1. HTML Boilerplate (Mandatory)

Your file must include:

- `<!DOCTYPE html>`
- `<html>`
- `<head>`
  - `<meta charset="UTF-8">`
  - `<title>`
  - `<style>` (Internal CSS required)

- `<body>`

You must also use inline CSS on at least one HTML element.

---

## 2. CSS Syntax

Follow proper CSS syntax:

```
selector {
  property: value;
}
```

- End each declaration with a semicolon.
- Use correct property names.
- Always include units where required (e.g., px).

---

## 3. Selectors

Your project must demonstrate all of the following selectors:

- Element selector (example: `p { }`)
- Class selector (example: `.card { }`)
- ID selector (example: `#profile { }`)
- Universal selector (example: `* { }`)

Use the universal selector to remove default margin and padding.

---

## 4. Profile Section (ID Selector Practice)

Create a section:

```
<section id="profile">
```

Inside it include:

- One heading
- One paragraph
- One image

Style `#profile` using:

- Background color
- Padding
- Border
- Width
- Margin

This section must clearly demonstrate the full Box Model.

---

## 5. Product Cards (Class Selector Practice)

Create two product cards using:

```
<div class="card">
```

Each card must include:

- A heading
- A short description
- Old and new price

Style `.card` using:

- Border (width, style, color)
- Border-radius
- Padding
- Margin
- Background color
- Fixed width

This demonstrates reusable styling using class selectors.

---

## 6. Color Practice

Use all four types of color values:

- Named color
- Hex value
- RGB value
- HSL value

Apply them to different elements.

---

## 7. Background Properties

Demonstrate:

- `background-color`
- `background-image`
- `background-repeat`
- `background-position`
- Shorthand `background` property

At least one section must contain a background image.

---

## 8. Border Properties

Demonstrate:

- `border-width`
- `border-style`
- `border-color`
- Shorthand `border`
- `border-radius`

---

## 9. Margin and Padding

Clearly demonstrate the difference between:

- Margin (space outside the border)
- Padding (space inside the border)

Explain both using CSS comments.

---

## 10. Height and Width

Use:

- `width` in pixels
- `width` in percentage
- `min-width`
- `max-width`

Explain at least one of these properties using a CSS comment.

---

## 11. Box Model Explanation

Inside your CSS, include a comment explaining:

```
Box Model Layers:
1. Content
2. Padding
3. Border
4. Margin
```

At least one element must visually demonstrate all four layers.

---

## 12. CSS Comments

Include:

- At least five meaningful CSS comments
- At least one comment explaining a common CSS mistake

Example:

```
/* Wrong: width: 300; Missing unit (px) */
```

---

## 13. Common CSS Errors Awareness

Demonstrate understanding of common mistakes such as:

- Missing semicolon
- Missing unit
- Typo in property name
- Incorrect selector usage

At least one incorrect example must be written and commented out.

---

# Rules

- Use internal CSS only
- Do not use an external CSS file
- Do not use Flexbox or Grid
- Do not use JavaScript
- Keep the layout simple
- Focus on demonstrating core CSS concepts

---

# Learning Outcome

After completing this task, students will be able to:

- Write correct CSS syntax
- Use different types of selectors properly
- Apply multiple color formats
- Use background and border properties correctly
- Understand and demonstrate the Box Model
- Distinguish clearly between margin and padding
- Avoid common beginner CSS errors

---

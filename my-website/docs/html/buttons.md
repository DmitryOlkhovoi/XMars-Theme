---
id: buttons
title: Buttons
sidebar_label: Buttons
---

Use XMars-UI custom button styles for actions in forms, dialogs, and more with support for multiple sizes, states, and more.

## Examples
XMars-UI includes several predefined button styles, each serving its own semantic purpose, with a few extras thrown in for more control.
<p>
    <button type="button" class="btn ml-1">Subscribe</button>
    <button type="button" class="btn accent ml-1">Subscribe</button>
    <button type="button" class="btn primary ml-1">Subscribe</button>
</p>

#### HTML

```html
<button type="button" class="btn">Subscribe</button>
<button type="button" class="btn accent">Subscribe</button>
<button type="button" class="btn primary">Subscribe</button>
```

#### React JSX

```jsx
<Button>Subscribe</Button>
<Button accent>Subscribe</Button>
<Button primary>Subscribe</Button>
```

## Button tags
The .btn classes are designed to be used with the `<button>` element. However, you can also use these classes on `<a>` or `<input>` elements (though some browsers may apply a slightly different rendering).

When using button classes on `<a>` elements that are used to trigger in-page functionality (like collapsing content), rather than linking to new pages or sections within the current page, these links should be given a role="button" to appropriately convey their purpose to assistive technologies such as screen readers.

<p>
    <a role="button" href="#" class="btn primary">Link</a>
    <button type="button" class="btn primary ml-1">Button</button>
    <input type="button" class="btn primary ml-1" value="Input" />
    <input type="submit" class="btn primary ml-1" value="Submit" />
    <input type="reset" class="btn primary ml-1" value="Reset" />
</p>

```html
<a role="button" href="#" class="btn primary">Link</a>
<button type="button" class="btn primary">Button</button>
<input type="button" class="btn primary" value="Input" />
<input type="submit" class="btn primary" value="Submit" />
<input type="reset" class="btn primary" value="Reset" />
```

## Sizes
Fancy larger or smaller buttons? Add `big` or `small` for additional sizes.

Create block level buttons—those that span the full width of a parent—by adding [Sizing Utilities]() class `w-full`.

<p>
    <button type="button" class="btn primary uppercase w-full">Subscribe</button>
</p>

#### HTML
```html
<button type="button" class="btn primary uppercase w-full">Subscribe</button>
```

#### React JSX
```jsx
<Button primary additionalClass="uppercase w-full">Subscribe</Button>
```
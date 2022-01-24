---
id: my-doc-id
title: My document title
description: My document description
slug: /my-custom-url
---

## Markdown heading

Markdown text with [links](./hello)

Let's see how to [Create a blog post](./tutorial-basics/create-a-blog-post).

![Docusaurus logo](/img/docusaurus.png)

```jsx title="src/components/test.js"
const test = 'test';
```

這是 `tip` 類型的 Admonition

:::tip My tip

Use this awesome feature option

:::

以下是 `danger` 類型的 Admonition

:::danger My

Danger!!!

:::

## MDX

export const Highlight = ({children, color}) => (
<span
style={{
  backgroundColor: color,
  borderRadius: '20px',
  color: '#fff',
  padding: '10px',
  cursor: 'pointer',
}}
onClick={() => {
alert(`You clicked the color ${color} with label ${children}`)
}}>
{children}
</span>
);

This is <Highlight color="#25c2a0">Docusaurus green</Highlight> !

This is <Highlight color="#1877F2">Facebook blue</Highlight> !

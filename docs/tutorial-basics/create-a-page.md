---
sidebar_position: 1
---

# Create a Page

Add **Markdown or React** files to `src/pages` to create a **standalone page**:

- `src/pages/index.js` → `localhost:3000/`
- `src/pages/foo.md` → `localhost:3000/foo`
- `src/pages/foo/bar.js` → `localhost:3000/foo/bar`

## Create your first React Page

Create a file at `src/pages/my-react-page.js`:

```jsx title="src/pages/my-react-page.js"
import React from 'react';
import Layout from '@theme/Layout';

export default function MyReactPage() {
  return (
    <Layout>
      <h1>My React page</h1>
      <p>This is a React page</p>
    </Layout>
  );
}
```
  <iframe
      id="inlineFrameExample"
      title="Javascript"
      frameborder="0" 
      scrolling="no"
      height="400"
      width="700"
      src="https://stackblitz.com/edit/js-dfhq4e?ctl=1&embed=1&file=index.js&hideExplorer=1"
      >
  </iframe>

A new page is now available at [http://localhost:3000/my-react-page](https://stackblitz.com/edit/js-dfhq4e?ctl=1&embed=1&file=index.js&hideExplorer=1).


## Create your first Markdown Page

Create a file at `src/pages/my-markdown-page.md`:

```mdx title="src/pages/my-markdown-page.md"
# My Markdown page

This is a Markdown page
```

A new page is now available at [http://localhost:3000/my-markdown-page](http://localhost:3000/my-markdown-page).

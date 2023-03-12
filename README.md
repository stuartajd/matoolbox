# MAToolbox 🛠️

A collection of tools to help make your MA life easier.

## How do I add a new tool?

There is a `template.html` page in the root of this directory. Copy that into the `/docs` directory to build your first tool.

Each of the tools should have a name and description and be built using the template and use Vue JS.

Once the tool has been built, ensure that it has a unique page name within the `/docs` directory.

You should also add the tool information to the `tools` array within the `index.html` page. This will allow it to render on the main page.

```js
{
    header: "Unique tool title",
    description: "A brief description of the tool",
    link: "/page-url.html"
},
```

Create a PR and we'll get it merged into `main` after a review.
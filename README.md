# Next.js Client-starter /w Sanity

> An _**opninionated**_ Next.js/sanity starter template created for myself. It uses Next.js with server-side generation and tailwind for a good workflow and efficient results.

## Table of contents

- [The stack (Technologies)]("#tech-stack")
- [Folder structure]("#folder-structure")
- [Examples]("#examples")
- [Things to fix/add]("#todo")

## Tech Stack

We use **Next.js**, **SanityCMS**, **TailwindCSS**

Groq, clsx, headlessui, fuse-js(fuzzy search)

## Folder structure

```javascript
/src
  /components // All components except the once in ui & layout
    [Name].tsx // If you are builing component for navbar, do NavbarItem. Dont use separate folders.
  /pages // Next.js pages
    /api
      [Route].ts
    [Route].tsx
  /ui // Simple ui-components
  /layouts // Layout-components used in pages
  /hooks // hooks
  /context // eg: UserContext.ts
    [Name]Context.ts
  /types // Type-declerations
    [Name]Type.ts // User-type: UserType.ts, not User.ts
  /utils
    [Name].ts // eg: Client.ts (These should have a good api)
```

A basic understanding of the component-tree system:

Pages:

Put together layout, components and modules.
Components use ui-components to build up bigger components
Components can also be without ui-components ofcourse.

Examples of UI-components:
Buttons, text-styles, image-wrappers, navitem-styles

Examples of components:
Navbars, button-groups,
Basically everything that is put into the different layout options.

## Examples

## Todo

- [] Add sentry error-tracking
- [] Add github workflows and testing ?

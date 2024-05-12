# Nuxt 3 Essentials

## Overview

### Installation and Configuration

get started:

- quick start guide: [https://nuxt.com/docs/getting-started](https://nuxt.com/docs/getting-started)
- create project `npx nuxi init nuxt3-app`

directories:

- /layouts, create custom layouts for various part of the site, and then assign a component to use the layout with the `layout` keyword
  - ![alt text](docs/image.png)
- /pages, create our URL structure for our app
  - ![alt text](docs/image-1.png)

### Creating the URL Structure For Pages

the URL structure is `mysite.com/currency/{id}`, where {id} is the dynamic value passed in to the component.

steps:

- create a `/currency` folder under `/pages` => `/pages/currency`
- in the `/currency` directory create a Vue component named `[id].vue` (with the brackets)

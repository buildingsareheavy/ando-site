---
layout: layouts/post.njk
title: "Test Title #1"
description: "Test Description #1"
---
Test post body #1

```bash
    git clone https://github.com/buildingsareheavy/ando.git && cd ando
```

```bash
less blueprints
```

```js
const syntaxHighlight = require("@11ty/eleventy-plugin-syntaxhighlight");

module.exports = function(eleventyConfig) {
    eleventyConfig.addPassthroughCopy('images')
    eleventyConfig.addPassthroughCopy('admin')
    eleventyConfig.addPlugin(syntaxHighlight);
  };
```


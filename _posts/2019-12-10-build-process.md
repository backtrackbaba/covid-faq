---
title: Build Process
subtitle: Cras at dolor eget urna varius faucibus tempus in elit. Cras a dui imperdiet, tempus metus quis, pharetra turpis.
categories: [customization, development]
author: evan
---

### Build process
Install [UIkit](https://getuikit.com/) font end framework dependency via Npm:
```bash
npm install
```
Enable live browser reload with the following:
```bash
bundle exec jekyll s --livereload
```

Use the following commands to compile js scripts:
```bash
npm run dev
```
Compile and minify:
```bash
npm run build
```

### Hooks
There are four hook inlude files that simplify adding content or scripts in the theme locations:
- `_includes/hook-head.html`
- `_includes/hook-pre-closing-body.html`
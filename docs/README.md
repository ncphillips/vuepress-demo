---

---
# VuePress + Forestry = ❤️

## Editing Files

### File Formats

Markdown and HTML files can be edited with Forestry.

Extensions:

* `md`
* `.markdown`
* `.html`
* `.htm`

### Front Matter

VuePress supports 3 front matter formats:

* YAML
* JSON
* TOML

Currently Forestry only supports YAML and JSON.

## Media

VuePress supports 4 methods of referencing media in markdown files:

1. Absolute external URLs
2. Absolute internal URLs – The path on the built site
3. Relative paths from the source repo
4. Alias paths

Currently, Forestry only supports the first two options.

Forestry only let's you manage media in a single directory. By default, this will by the `.vuepress/public` directory.

### Supported Media Storage Providers

* Git
* Cloudinary

## What's Missing?

### Forestry Features

VuePress support is still very early with Forestry. You'll notice that a few features that are available to Hugo and Jekyll sites are missing for VuePress. Here's a shortlist of those features:

* Data files
* Menus
* Previews
* Build & Deploy
* Tightly integrated Published/Draft statuses
  * Note: This is because VuePress does not have drafts yet.
+++
title = 'Hugo Layouts'
linkTitle = 'Home'
date = 2023-07-20T12:02:16-07:00
draft = false
details = ''
description = "Hugo layout lookup order"
+++

see [Hugo discourse post](https://discourse.gohugo.io/t/multi-level-branch-bundle-works-but-doesnt-use-corresponding-level-layouts/45434) for details

{{< rawhtml >}}
<table>
<tbody>
<tr>
<td class="tree">
<pre>
➜  hugo-layouts git:(main) ✗ tree content
content
├── <span class="active">_index.md</span>
├── about
│   ├── _index.md
│   ├── projects
│   │   ├── _index.md
│   │   ├── icedig
│   │   │   ├── img
│   │   │   │   └── icedig.png
│   │   │   └── index.md
│   │   └── mudwrap
│   │       ├── img
│   │       │   └── mudwrap.jpg
│   │       └── index.md
│   └── publications
│       └── _index.md
└── philosophy
    └── _index.md
</pre>
</td>
<td class="tree">
<pre>
➜  hugo-layouts git:(main) ✗ tree layouts
layouts
├── _default
│   ├── <span class="always-active">baseof.html</span>
│   ├── <span class="active">home.html</span>
│   ├── list.html
│   └── single.html
├── about
│   ├── list.html
│   ├── projects-list.html
│   ├── projects-single.html
│   └── single.html
├── partials
└── shortcodes
</td>
</tr>
</tbody>
</table>
{{< /rawhtml >}}

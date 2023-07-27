+++
title = 'Mudrap'
date = 2023-07-20T11:29:41-07:00
draft = false
#layout = 'projects-single'
+++

{{< rawhtml >}}
<table>
<tbody>
<tr>
<td class="tree">
<pre>
➜  hugo-layouts git:(main) ✗ tree content
content
├── _index.md
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
│   │       └── <span class="active">index.md</span>
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
│   ├── home.html
│   ├── list.html
│   └── single.html
├── about
│   ├── list.html
│   ├── projects-list.html
│   ├── <span class="active">projects-single.html</span>
│   └── single.html
├── projects
│   ├── list.html
│   └── <span class="active">single.html</span>
├── partials
└── shortcodes
</td>
</tr>
</tbody>
</table>
{{< /rawhtml >}}

![a mudwrap](img/mudwrap.jpg)

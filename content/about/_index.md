+++
title = 'About'
date = 2023-07-20T11:28:51-07:00
draft = false
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
│   ├── <span class="active">_index.md</span>
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
│   ├── home.html
│   ├── list.html
│   └── single.html
├── about
│   ├── <span class="active">list.html</span>
│   └── single.html
├── partials
└── shortcodes
</td>
</tr>
</tbody>
</table>
{{< /rawhtml >}}

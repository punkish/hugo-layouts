+++
title = 'Projects'
date = 2023-07-20T11:29:11-07:00
draft = false
[cascade]
    type = 'projects'
+++


```
# frontmatter in content/projects/_index.md
# this enables all children of *projects* to use 
# layouts/projects/<list|single>.html
[cascade]
    type = 'projects'
```

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
│   │   ├── <span class="active">_index.md</span>
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
│   ├── list.html
│   └── single.html
├── projects
│   ├── <span class="active">list.html</span>
│   └── single.html
├── partials
└── shortcodes
</td>
</tr>
</tbody>
</table>
{{< /rawhtml >}}


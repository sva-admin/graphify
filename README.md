# graphify

Turn any folder (code, docs, papers, images, videos) into a persistent, queryable knowledge graph with god nodes, community detection, and query, path, and explain tools.

> **Transparency**
>
> This is Silicon Valley Academy's modified version of [graphify](https://github.com/safishamsi/graphify) by safishamsi, published under the original Apache-2.0 license.

## Install

Paste this into Claude Code:

```
Install the graphify skill from github.com/sva-admin/graphify
```

The skill installs its own `graphifyy` Python package on first run, so there is nothing else to set up.

## Use it

```
/graphify                                    # graph the current directory
/graphify <path>                             # graph a specific folder
/graphify https://github.com/<owner>/<repo>  # clone a repo, then graph it
/graphify <path> --update                    # re-extract only what changed
```

You get three outputs: an interactive HTML graph, GraphRAG-ready JSON, and a plain-language `GRAPH_REPORT.md`. Once `graphify-out/` exists in a project, architecture and relationship questions get answered from the graph instead of from a blind file search.

## Learn it free

We teach this skill, start to finish, in a free lesson:

[Map your knowledge](https://loop.sv-academy.org/articles/map-your-knowledge)

## More from Silicon Valley Academy

- All of our published skills: [github.com/sva-admin/claude-skills](https://github.com/sva-admin/claude-skills)
- Courses and free lessons: [sv-academy.org](https://sv-academy.org)

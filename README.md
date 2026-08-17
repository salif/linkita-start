# Linkita start

Start blogging in minutes with [Zola](https://www.getzola.org/) and [Linkita](https://github.com/salif/linkita).

![Screenshot of Linkita theme](https://cdn.jsdelivr.net/gh/salif/linkita@main/screenshot.png)

## Quick start

1. On the top right of this page, click "Use this template" → "Create a new repository"
2. Replace placeholders in `content/_index.md` and `zola.toml`
3. Save your profile photo to `static/profile.png` (or change the path to your image in `zola.toml`)
4. Start writing in `content/blog/`. See `content/blog/hello.md` for an example

**Note**: an error like `Tried to build search index for language ko which is not supported`,
means Zola does not support search for that language.
To disable search, set `build_search_index = false` in `zola.toml`

> [!TIP]
> Take a look through `zola.toml` to customise further.

## Local development

1. [Install Zola](https://www.getzola.org/documentation/getting-started/installation/)
2. Clone your repository
3. Run `git submodule update --init --recursive`
4. Run `zola serve`
5. Visit http://127.0.0.1:1111/

## Deployment

Refer to the [Zola documentation](https://www.getzola.org/documentation/deployment/overview/)

## Updating Linkita

```bash
git submodule update --remote themes/linkita
```

See [managing versions](https://github.com/salif/linkita#managing-versions).

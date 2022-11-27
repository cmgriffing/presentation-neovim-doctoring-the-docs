# The Second Hack

<div class="notes">
Teej told me about the treesitter grammar for nvimdoc files.
</div>

## Neovim source: gen_help_html (outline)

![](./assets/gen_help_html-outline.png)

## Neovim source: gen_help_html (visit_node)

![](./assets/gen_help_html-visit_node.png)

## Neovim source: gen_help_html (visit_node:codeblock)

![](./assets/gen_help_html-visit_node-codeblock.png)

## Neovim source: gen_help_html (gen_css)

![](./assets/gen_help_html-gen_css.png)

## Neovim source: gen_help_html (logo, etc)

![](./assets/gen_help_html-logo_etc.png)

## Neovim source: gen_help_html (toc)

![](./assets/gen_help_html-toc.png)

## Forking neovim (why)

- Reduced repetition in output
- Easier custom theming and light/dark mode

## Forking neovim (example)

Before:

```
elseif node_name == 'argument' then
  return ('%s<code>{%s}</code>'):format(ws(), text)
```

After:

```
elseif node_name == 'argument' then
  return ('%s`{%s}`'):format(ws(), text)
```

## Who is the coolest doctor in the hospital?

## The hip specialist

![](./assets/dancing-doctor.gif)

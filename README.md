# **The Propaganda**

### It is a blog website build with the Hugo framework - https://gohugo.io/

### The theme is called Archie - https://github.com/athul/archie

## Adding Images 📁

Place any pictures or media you want to reference in future posts under `static/images/` (create the folder if it doesn't exist). Hugo will copy everything in
`static/` straight to the site root, so you can reference `src="/images/your-file.jpg"` from your markdown.

Example:

```markdown
{{< figure src="/images/post8.jpg" title="Girl in the rain" class="center-image" >}}
```

This keeps assets organized and avoids cluttering the top level of `static/`. You can also create further subfolders (e.g. `static/images/posts/`).

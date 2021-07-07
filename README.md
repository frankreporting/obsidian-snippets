# My Obsidian CSS Snippets

## About

My stash for CSS snippets I've used to customize [Obsidian](https://obsidian.md), my go-to note-taking app.

---

### [WYSIWIG-like.css](https://github.com/frankreporting/obsidian-snippets/blob/main/WYSIWYG-like.css)

This one gives you a WYSIWIG-like interface directly in the edit view, as opposed to having to switch to preview mode. It makes Obsidian behave a little more like [Typora](https://typora.io) — in this case, your markdown becomes invisible and is replaced with rendered HTML on all but the active line. This is basically a mod and mashup of Santi Younger's [Org-sidian-Bullets](https://github.com/santiyounger/Org-sidian-Bullets) and the WYSIWYG option in Ozan Tellioglu's [Ozan's Image in Editor plugin](https://github.com/ozntel/oz-image-in-editor-obsidian), so major thanks and shoutouts to both!

If you couple this snippet with Ozan's Image in Editor plugin, you get something like this:

![](demo/WYSIWYG-demo.gif)

**NOTE:** This isn't a perfect solution, but I've been pretty happy with it. There appears to be an occasional, unavoidable conflict between the markdown line length and the "rendered" line length that make it impossible for you to get the cursor to the proper end of the line. I've found a fairly consistent fix is to delete a character or two and then re-type them. This seems to reset the cursor position and line length so everything is in sync again.

---

### [minimal-theme-link-fix.css](https://github.com/frankreporting/obsidian-snippets/blob/main/minimal-theme-link-fix.css)

If you use Stephan Ango's [Minimal Theme](https://github.com/kepano/obsidian-minimal), then this simply flips the script on what text to emphasize in your hyperlinks, highlighting the linked text and muting the URL string, more in line with the rendered HTML. Originally had it in my WYSIWYG CSS snippet but it seemed better not to muddle things with theme-specific tweaks.

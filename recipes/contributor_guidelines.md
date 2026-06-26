## Contributor Guidelines

### Markdown basics
Recipes are written in Markdown. You only need a few basics:

- `##` for section headings
- `**text**` for bold
- `-` for bullet point lists
- `1.` for numbered steps

Refer to `recipe_template.md` for the expected structure — all the headings are already in place for you to fill in.

---

### Image requirements
Include one photo of the finished recipe. Requirements:

- **Format:** JPG or PNG
- **Minimum size:** 500×500 pixels
- **Content:** the finished dish, as prepared from the recipe

To add your image, upload it to the `images` folder in the repository and reference it in your recipe file as:

```markdown
![Recipe name](../images/your-image-file.jpg)
```

---

### Submission process

1. Open `recipe_template.md` and click the **Raw** button
2. Select all and copy the content
3. Navigate to the relevant cuisine subfolder of the recipes folder and click **Add file → Create new file**
4. In the filename field, type your recipe name followed by `.md`. This should be lowercase, derived from the title of the recipe, with spaces replaced by underscores, (e.g. `chocolate_cake.md`)
5. Paste the copied content into the editor body
6. Fill in the template fields with your recipe details
7. Scroll down to **Commit changes**, add a short description (e.g. `Add chocolate cake recipe`), and click **Commit changes**

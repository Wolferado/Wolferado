# Repository Name (not like in the name)[^1]

# Headings

# A first-level heading
## A second-level heading
### A third-level heading
(will provide Links to the headings as well)

<hr>

**This is bold text**

_This text is italicized_

~~This was mistaken text~~

**This text is _extremely_ important**

***All this text is important***

This is a <sub>subscript</sub> text

This is a <sup>superscript</sup> text

<hr>

> Text that is a quote

Use `git status` to list all new or modified files that haven't yet been committed.

Some basic Git commands are:
```
git status
git add
git commit
```

The background color is `#ffffff` for light mode and `#000000` for dark mode.

Color HEX: `#0969DA`

Color RGB: `rgb(9, 105, 218)`

Color HSL: `hsl(212, 92%, 45%)`

<hr>

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

<hr>

Example for the links: This site was built using [GitHub Pages](https://pages.github.com/).

Example for relative links (inside the projects): [Contribution guidelines for this project](docs/CONTRIBUTING.md)

Inside the branch: `/assets/images/electrocat.png`

Another branch: `/../main/assets/images/electrocat.png`

In issues, pull requests and comments of the repository: `../blob/main/assets/images/electrocat.png?raw=true`

In a .md file in another repository: `/../../../../github/docs/blob/main/assets/images/electrocat.png`

In issues, pull requests and comments of another repository: `../../../github/docs/blob/main/assets/images/electrocat.png?raw=true`

Images:

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://freeiconshop.com/wp-content/uploads/edd/image-outline-filled.png)

Prefer-color-scheme:

```
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>
```

<hr>

- George Washington
* John Adams
+ Thomas Jefferson

1. James Madison
2. James Monroe
3. John Quincy Adams

1. First list item
   - First nested list item
     - Second nested list item
    
- [x] #739 (bug)
- [ ] https://github.com/octo-org/octo-repo/issues/740 (issue)
- [ ] Add delight to the experience when all tasks are complete :tada:
- [ ] \(Optional) Open a followup issue

<hr>

Mentions: @github/support What do you think about these updates?

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

<hr>

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

<hr>

<!-- This content will not appear in the rendered Markdown -->

Ignoring markdown: Let's rename \*our-new-project\* to \*our-old-project\*.

<hr>

[^1]: [Source of the Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
[^2]: My reference.
[^3]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

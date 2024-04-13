- 👋 Hi, I’m @Epiayo
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Epiayo/Epiayo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


Basic writing and formatting syntax

Create sophisticated formatting for your prose and code on GitHub with simple syntax.

In this article

Headings

Styling text

Quoting text

Quoting code

Supported color models

Links

Section links

Relative links

Images

Lists

Task lists

Mentioning people and teams

Referencing issues and pull requests

Referencing external resources

Uploading assets

Using emojis

Paragraphs

Footnotes

Alerts

Hiding content with comments

Ignoring Markdown formatting

Disabling Markdown rendering

Further reading

Headings") 0% 0% / cover; mask: url("data:image/svg+xml;charset=utf8,"); background-color: var(--color-fg-subtle);">

To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the hierarchy level and typeface size of the heading.

# A first-level heading ## A second-level heading ### A third-level heading 

When you use two or more headings, GitHub automatically generates a table of contents that you can access by clicking  within the file header. Each heading title is listed in the table of contents and you can click a title to navigate to the selected section.

Styling text") 0% 0% / cover; mask: url("data:image/svg+xml;charset=utf8,"); background-color: var(--color-fg-subtle);">

You can indicate emphasis with bold, italic, strikethrough, subscript, or superscript text in comment fields and .md files.

StyleSyntaxKeyboard shortcutExampleOutputBold** ** or __ __Command+B (Mac) or Ctrl+B (Windows/Linux)**This is bold text**This is bold textItalic* * or _ _     Command+I (Mac) or Ctrl+I (Windows/Linux)_This text is italicized_This text is italicizedStrikethrough~~ ~~None~~This was mistaken text~~This was mistaken textBold and nested italic** ** and _ _None**This text is _extremely_ important**This text is extremely importantAll bold and italic*** ***None***All this text is important***All this text is importantSubscript<sub> </sub>NoneThis is a <sub>subscript</sub> textThis is a subscript textSuperscript<sup> </sup>NoneThis is a <sup>superscript</sup> textThis is a superscript textQuoting text") 0% 0% / cover; mask: url("data:image/svg+xml;charset=utf8,"); background-color: var(--color-fg-subtle);">

You can quote text with a >.

Text that is not a quote > Text that is a quote 

Quoted text is indented, with a different type color.

Note: When viewing a conversation, you can automatically quote text in a comment by highlighting the text, then typing R. You can quote an entire comment by clicking , then Quote reply. For more information about keyboard shortcuts, see "Keyboard shortcuts."

Quoting code") 0% 0% / cover; mask: url("data:image/svg+xml;charset=utf8,"); background-color: var(--color-fg-subtle);">

You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted. You can also press the Command+E (Mac) or Ctrl+E (Windows/Linux) keyboard shortcut to insert the backticks for a code block within a line of Markdown.

Use `git status` to list all new or modified files that haven't yet been committed. 

To format code or text into its own distinct block, use triple backticks.

Some basic Git commands are: ``` git status git add git commit ``` 

For more information, see "Creating and highlighting code blocks."

If you are frequently editing code snippets and tables, you may benefit from enabling a fixed-width font in all comment fields on GitHub. For more information, see "About writing and formatting on GitHub."

Supported color models") 0% 0% / cover; mask: url("data:image/svg+xml;charset=utf8,"); background-color: var(--color-fg-subtle);">

In issues, pull requests, and discussions, you can call out colors within a sentence by using backticks. A supported color model within backticks will display a visualization of the color.

The background color is `#ffffff` for light mode and `#000000` for dark mode. 

Here are the currently supported color models.

ColorSyntaxExampleOutputHEX`#RRGGBB``#0969DA`RGB`rgb(R,G,B)``rgb(9, 105, 218)`HSL`hsl(H,S,L)``hsl(212, 92%, 45%)`

Notes:

A supported color model cannot have any leading or trailing spaces within the backticks.The visualization of the color is only supported in issues, pull requests, and discussions.

Links") 0% 0% / cover; mask: url("data:image/svg+xml;charset=utf8,"); background-color: var(--color-fg-subtle);">

You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ). You can also use the keyboard shortcut Command+K to create a link. When you have text selected, you can paste a URL from your clipboard to automatically create a link from the selection.

You can also create a Markdown hyperlink by highlighting the text and using the keyboard shortcut Command+V. If you'd like to replace the text with the link, use the keyboard shortcut Command+Shift+V.

This site was built using [GitHub Pages](https://pages.github.com/).

Note: GitHub automatically creates links when valid URLs are written in a comment. For more information, see "Autolinked references and URLs."

Section links") 0% 0% / cover; mask: url("data:image/svg+xml;charset=utf8,"); background-color: var(--color-fg-subtle);">

You can link directly to a section in a rendered file by hovering over the section heading to expose .

Relative links") 0% 0% / cover; mask: url("data:image/svg+xml;charset=utf8,"); background-color: var(--color-fg-subtle);">

You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.

A relative link is a link that is relative to the current file. For example, if you have a README file in root of your repository, and you have another file in docs/CONTRIBUTING.md, the relative link to CONTRIBUTING.md in your README might look like this:

[Contribution guidelines for this project](docs/CONTRIBUTING.md) 

GitHub will automatically transform your relative link or image path based on whatever branch you're currently on, so that the link or path always works. The path of the link will be relative to the current file. Links starting with / will be relative to the repository root. You can use all relative link operands, such as ./ and ../.

Your link text should be on a single line. The example below will not work.

[Contribution guidelines for this project](docs/CONTRIBUTING.md) 

Relative links are easier for users who clone your repository. Absolute links may not work in clones of your repository - we recommend using relative links to refer to other files within your repository.

Images") 0% 0% / cover; mask: url("data:image/svg+xml;charset=utf8,"); background-color: var(--color-fg-subtle);">

You can display an image by adding ! and wrapping the alt text in [ ]. Alt text is a short text equivalent of the information in the image. Then, wrap the link for the image in parentheses ().

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

GitHub supports embedding images into your issues, pull requests, discussions, comments and .md files. You can display an image from your repository, add a link to an online image, or upload an image. For more information, see "Uploading assets."

Note: When you want to display an image that is in your repository, use relative links instead of absolute links.

Here are some examples for using relative links to display an image.

ContextRelative LinkIn a .md file on the same branch/assets/images/electrocat.pngIn a 



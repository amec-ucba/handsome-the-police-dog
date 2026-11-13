# 📄 Handsome the Police Dog

Code your very first web page by turning plain text about Handsome, Cincinnati's first
unofficial police dog, into a basic HTML page.

## 🎯 Overview

In this coding exercise, you will start with plain text about **Handsome** and turn that
text into a working HTML web page. Along the way, you will learn some of the most important
beginner concepts in web design: file organization, file extensions, Visual Studio Code,
HTML page structure, semantic HTML elements, image elements, and attributes.

Don't worry about making the page look interesting yet. There is no CSS in this exercise.
The goal right now is to learn how to build the **structure** of a web page. Later, CSS
will let you control colors, fonts, layout, spacing, and visual design.

The page will look plain when you are finished. **That is expected.** Plain HTML is
supposed to look simple before CSS is added.

> [!IMPORTANT]
> **The companion videos for this exercise are in Canvas**, on the assignment page. They
> walk you through every step, so watch them there instead of working from this file
> alone.

## 🧠 What You Will Learn

By completing this exercise, you will practice how to:

- Open a full project folder in Visual Studio Code
- Explain why file extensions such as `.txt`, `.html`, `.jpg`, and `.png` matter
- Rename a plain text file so it becomes an HTML file
- Create the basic structure of an HTML document
- Use semantic HTML elements such as headings and paragraphs
- Add images to a web page using the `img` element
- Use attributes such as `src` and `alt`
- Preview your HTML page in a browser

## 🪟 Windows Users: Turn On File Extensions First

Windows hides file extensions by default, which makes it hard to tell whether a file is
really an HTML file, a text file, or an image. You are going to rename a `.txt` file to an
`.html` file, so you need to see the full file name. Otherwise you can end up with
`index.html.txt` and not know it.

Canvas has a support page showing how to turn file extensions on. Mac users can skip this
step.

## 🎬 Watch the Videos in Canvas and Follow Along

The screencast videos are on this assignment's page in **Canvas**, not in this repo. They
walk you through the entire exercise. Watch them **in order** and follow along in Visual
Studio Code. Pause whenever you need time to finish a step — it is normal to pause,
rewind, and rewatch parts of a coding demonstration.

You are not expected to memorize everything right away. This first exercise is about
getting comfortable opening project files, using VS Code, typing HTML, saving your work,
and checking your page in a browser.

Each video builds on the previous one, so please don't skip ahead.

| Video | What you will do |
| --- | --- |
| **Part 1 — Setting Up** | Get the project folder ready, open it in VS Code, and prepare the starter file for coding. |
| **Part 2 — Basic HTML Structure** | Create the basic structure of an HTML document: the document type, `html`, `head`, `title`, and `body` elements. |
| **Part 3 — Marking Up the Content** | Identify the purpose of each piece of content and mark it up with semantic HTML elements, including headings and paragraphs. |
| **Part 4 — Adding Images** | Replace the image placeholders with `img` elements and learn how the `src` and `alt` attributes work. |
| **Part 5 — Submitting the Files** | Review the finished project folder before you submit. |

> [!IMPORTANT]
> **A few steps in this repo are different from the videos.** Follow the videos for the
> HTML, and follow this repo for getting your files and submitting:
>
> - **Getting the starter files (Part 1):** don't download a ZIP. Create your own repo
>   from this template and open it with GitHub Desktop, as described in the
>   [Getting Started guide](GETTING_STARTED.md).
> - **Naming your file:** rename `handsome.txt` to **`index.html`**, whatever name the
>   video uses. GitHub Pages only serves `index.html` at your site's root URL; any other
>   name gives you a 404. Rename the file — don't create a second one.
> - **Submitting (Part 5):** don't zip your folder or upload a file. Publish your page to
>   GitHub Pages and submit a pull request URL in Canvas, as described in the
>   [Submitting guide](SUBMITTING.md).

> [!IMPORTANT]
> Open the entire project **folder** in VS Code, not a single HTML file. VS Code needs to
> see every file in the project for your images to work. Keep `index.html`,
> `handsome.jpg`, and `handsome-today.jpg` together in the root folder.

## 📂 Starter Files

| File | Purpose |
| --- | --- |
| `handsome.txt` | The plain text for the article. **Rename this to `index.html`** and add your markup to it. |
| `handsome.jpg` | Historical photo of Handsome. Goes in the first section. |
| `handsome-today.jpg` | Handsome on display today. Goes in the "Handsome Today" section. |

Inside `handsome.txt`, two lines mark where the images belong:

```
[replace this with the image handsome.jpg]
[replace this with the image handsome-today.jpg]
```

Delete each placeholder line and put an `<img>` element in its place.

## ✅ Before You Submit

Check the following:

- [ ] `handsome.txt` has been renamed to `index.html` — and is not accidentally named `index.html.txt`
- [ ] `index.html`, `handsome.jpg`, and `handsome-today.jpg` are all in the root folder of the repo
- [ ] The page has the basic HTML structure: `DOCTYPE`, `html`, `head`, `title`, and `body`
- [ ] The main page title is marked up as an `h1`
- [ ] The section headings — *The Policeman's Pal* and *Handsome Today* — are marked up as `h2` elements
- [ ] Each paragraph of article text is inside its own `p` element
- [ ] The copyright line at the end of the text is included on the page
- [ ] Both images appear when you preview the page in a browser
- [ ] Both images include useful `alt` text
- [ ] You saved your file
- [ ] The page is live on GitHub Pages and the URL is in your pull request

## 🛠️ Troubleshooting

If something is not working, check these common issues first:

- Did you save the file?
- Is the file named exactly `index.html`, with no hidden `.txt` on the end?
- Are the image file names in your `src` spelled exactly right, including `.jpg`?
- Are the images in the same folder as `index.html`?
- Did you accidentally move or delete a starter file?
- Is your visible page content inside the `body` element?
- Are your opening and closing tags in the correct places?
- Are there quotation marks around your attribute values?

**Having problems with the videos?**

- **Getting a warning about third-party cookies?** Try using Chrome. Safari's default
  security settings may prevent embedded Canvas videos from playing unless those settings
  are changed.
- **Getting an "Access Denied" error?** Refresh your browser. In many cases, the videos
  will load correctly after the page reloads.

## 📚 Resources

- [MDN — HTML basics](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Creating_the_content)
- [MDN — Headings and paragraphs](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Headings_and_paragraphs)
- [MDN — `<img>`: The Image Embed element](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/img)
- [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input) — paste your
  HTML in to catch unclosed tags
- [Cincinnati Police Historical Society](https://www.police-museum.org/)

---

The AI policy and submission instructions are in the [README](../README.md).

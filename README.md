# CSS Style Lab Studio

A one-file web app for learning UI design through a guided no-code builder.

Visitors first go through short guide pages, then design a reusable UI element, review what they learned, choose what to do next, and finally apply saved elements on a real page playground. The finished playground can be exported as a standalone HTML file.

## Live Project

Replace this with your GitHub Pages link after publishing:

```text
https://alven356.github.io/Homework-UI-Design-Guide/
```

## What the visitor can do

The visitor can design reusable CSS resources, learn what their choices mean in UI design, place those resources on a page playground, resize and arrange them, and download the final page as HTML.

## Main Features

### 1. Guided pages

The app starts with a guide instead of immediately showing a huge editor. Each guide page explains one part of the workflow:

1. What a reusable UI resource is
2. The difference between a component and a text block
3. How style choices change the feeling of a design
4. How structure, badges, and buttons affect the user’s attention
5. How saving a resource leads to building a real page

Each guide page includes a small “Try it” interaction so the visitor can test an idea before using the full editor.

### 2. Element designer

The element designer is separate from the page playground. This makes the app easier to understand because the visitor focuses on one task at a time.

The visitor can design:

- Styled UI components
- Text / markdown blocks

For components, the visitor can edit:

- Brand badge visibility
- Brand badge text
- Title
- Description
- Number of buttons, from 0 to 3
- Button text
- Shape
- Size
- Radius
- Color
- Transparency
- Blur
- Border
- Shadow

For text blocks, the visitor can use markdown:

```markdown
# H1 heading
## H2 heading
### H3 heading
Normal paragraph text
```

They can also adjust text size and alignment.

### 3. Element summary

After saving an element, the app shows a summary of what the visitor created.

This summary explains UI design ideas such as:

- Hierarchy
- Shape language
- Depth
- Reusable design systems

This helps the project feel more like a learning app instead of just a tool.

### 4. Choice page

After the summary, the visitor chooses what to do next:

- Design more elements
- Apply saved elements on a real page

This keeps the experience clear and avoids forcing the visitor to scroll through too many controls at once.

### 5. Page playground

The page playground is separate from the element designer. It is used for layout and exporting.

The visitor can:

- Add saved resources to the page
- Drag elements around
- Resize elements using the lower-right handle
- Edit selected elements
- Change page width
- Change page height
- Change background color
- Change background grid size
- Download the final page as a standalone HTML file

## Why I made this choice

A meaningful choice I made was to separate the app into guided pages, an element designer, a summary page, a choice page, and a real page playground. This makes the app easier to understand because visitors are not dropped into every tool at once.

## What I would try next

Next I would add a slideshow mode, where each playground page becomes one slide in an exported HTML presentation.

Other possible next steps:

- Add image uploads
- Add layer controls
- Add templates for ads and slides
- Add a project save/load file
- Add animation controls
- Add an export option for multiple pages

## Teacher Submission Sentences

### 1. Public GitHub Pages URL

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/
```

### 2. The visitor can ___.

The visitor can design reusable CSS resources, learn what each design choice means, place resources on a page playground, and export the result as HTML.

### 3. A choice I made was ___.

A choice I made was to separate the experience into guided pages, an element designer, a summary page, and a page playground so visitors can understand the workflow step by step.

### 4. Next I would add ___.

Next I would add a slideshow mode where each playground page becomes one presentation slide.

## How to Use the App

1. Open the website.
2. Read the guide pages.
3. Click **Start designing**.
4. Choose either a component or a text block.
5. Change the style and content.
6. Click **Save element and show summary**.
7. Read the summary of what you learned.
8. Choose whether to design more elements or apply them on a real page.
9. In the page playground, click **Use** on a saved resource.
10. Drag and resize elements.
11. Click **Download HTML** to export the final page.

## How to Publish on GitHub Pages

1. Create a GitHub repository.
2. Upload the app file as:

```text
index.html
```

3. Upload this file as:

```text
README.md
```

4. Go to the repository’s **Settings**.
5. Open **Pages**.
6. Set the source to **Deploy from a branch**.
7. Choose the `main` branch and `/root`.
8. Save.
9. Wait for GitHub Pages to create the public URL.

## File Structure

```text
project-folder/
├── index.html
└── README.md
```

## Built With

- HTML
- CSS
- JavaScript
- No build tools
- No API keys
- No external libraries

## Project Status

This is a finished Session 3 app because:

- The public URL can load on GitHub Pages.
- Multiple interactions work.
- A visitor can understand what to do through the guide pages.
- The app includes a meaningful design choice.
- The app names a clear next step.

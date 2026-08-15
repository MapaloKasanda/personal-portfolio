# HTML Website Development Assignment
STUDENT INFORMATION
NAME: MAPALO KASANDA
S.I.N: 2305865805
GIT HUB REPOSITORY: github.com/MapaloKasanda/personal-portfolio
# Question 2: HTML Elements

## 2.1 Which 5 elements did you find most challenging to implement and why?

### 1. `<table>`

The `<table>` element was challenging because it required an understanding of how rows, columns, headings, and different sections of a table work together. The `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, and `<td>` elements were used to organize information correctly.

### 2. `<form>`

The `<form>` element was challenging because several elements have to work together correctly. Elements such as `<label>`, `<input>`, `<textarea>`, and `<button>` were used to create the contact form.

### 3. `<fieldset>`

The `<fieldset>` element was challenging because it is used to group related form controls together. It helped organize the contact form into a clear structure.

### 4. `<details>`

The `<details>` element was challenging because it creates expandable content. It was used to allow additional information to be hidden until the user chooses to view it.

### 5. `<figure>`

The `<figure>` element was challenging because it is normally used together with an image and a caption. It was used with `<img>` and `<figcaption>` to present an image and its description.

---

## 2.2 How did you use semantic elements like `<section>`, `<article>`, `<header>`, and `<footer>` to structure your content?

Semantic HTML elements were used to give the website a clear and meaningful structure.

The `<header>` contains the website heading and navigation.

The `<nav>` contains links that allow visitors to move between different sections of the website.

The `<main>` contains the primary content of the webpage.

The `<section>` element divides the main content into logical areas.

The `<article>` element is used for individual pieces of information within the sections.

The `<aside>` contains additional information related to the main content.

The `<footer>` contains information at the bottom of the webpage.

Using semantic elements makes the website easier to understand, navigate, maintain, and access.

---

## 2.3 Which element was most useful for organizing your layout and why?

The `<section>` element was the most useful for organizing the layout.

It allowed the website to be divided into separate and meaningful areas. Each section could contain related information, making the webpage easier to navigate and understand.

---

# Question 3: HTML Attributes

## 3.1 Which 3 attributes were essential for making your website functional?

### 1. `href`

The `href` attribute was essential because it was used to create navigation links. It allows users to move between different sections or pages.

### 2. `id`

The `id` attribute was essential because it gives an HTML element a unique identifier. It can also be used with links to navigate directly to a specific section.

### 3. `src`

The `src` attribute was essential for displaying images. It specifies the location of the image that the browser should load.

---

## 3.2 How did you use the `class` and `id` attributes differently?

The `id` attribute is used to uniquely identify a particular element on a webpage.

For example:

```html
<section id="about">
```

The `about` ID identifies that particular section.

The `class` attribute is used to group multiple elements that have similar characteristics or are intended to receive the same styling.

Therefore, an `id` is normally used for a unique element, while a `class` can be shared by multiple elements.

---

## 3.3 Which attribute helped improve user experience the most and why?

The `alt` attribute helped improve the user experience because it provides alternative text for images.

If an image cannot be displayed, the alternative text can describe what the image represents. It also improves accessibility for people who use screen readers.

The `title` attribute can also provide additional information when users interact with certain elements.

---

# Question 4: Development Process

## 4.1 How did you plan your website structure before coding?

Before coding, the information that would appear on the website was identified and organized into logical sections.

The general structure was planned as follows:

1. Header and navigation
2. Main content
3. Different content sections
4. Additional information
5. Contact section
6. Footer

After planning the structure, appropriate HTML elements were selected for each part of the website.

The basic HTML document structure was then created before adding the individual sections.

---

## 4.2 What was your approach to testing and debugging your HTML?

The HTML was tested by opening the webpage in a web browser.

The following areas were checked:

- Whether the webpage loaded correctly.
- Whether navigation links worked.
- Whether images displayed correctly.
- Whether forms appeared correctly.
- Whether the content was properly organized.
- Whether all elements appeared in the correct locations.

When errors were found, the HTML code was reviewed for missing tags, incorrect nesting, and incorrect attributes. The errors were then corrected and the webpage was tested again.

---

## 4.3 What challenges did you face and how did you overcome them?

One challenge was meeting the requirement of using at least 25 different HTML elements.

This was overcome by selecting different elements for different purposes and using semantic HTML elements where appropriate.

Another challenge was meeting the requirement of using at least 15 different HTML attributes.

This was addressed by using attributes such as `id`, `href`, `title`, `src`, `alt`, `width`, `height`, `action`, `method`, `for`, `type`, `name`, `placeholder`, `rows`, and `cols`.

Another challenge was creating a semantic structure. This was overcome by using elements such as `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>`.

---

# Question 5: Git & GitHub Implementation

## 5.1 What Git commands did you use during development?

The Git commands used during development included:

```bash
git init
git status
git add .
git commit -m "Initial website structure"
git branch -M main
git remote add origin [Repository URL]
git push -u origin main
```

`git init` initializes a Git repository.

`git status` checks the current status of files.

`git add .` stages the project files.

`git commit` saves changes to the Git history.

`git branch -M main` sets the main branch name.

`git remote add origin` connects the local repository to the GitHub repository.

`git push` uploads the project to GitHub.

---

## 5.2 How many commits did you make and what was your commit message strategy?

The number of commits depends on the actual development history of the project.

Each commit should use a short and descriptive message explaining what was changed.

Examples of suitable commit messages include:

```text
Initial website structure
Added personal information
Added interests and skills
Added contact form
Updated README documentation
```

Descriptive commit messages make it easier to understand the development history and identify what was changed in each stage of the project.

---

## 5.3 Why is version control important for web development projects?

Version control is important because it keeps track of changes made to a project.

Git allows developers to:

- Save different versions of their work.
- Track changes.
- Recover previous versions.
- Work safely on projects.
- Collaborate with other developers.
- Maintain a history of the project.

GitHub also provides an online platform where projects can be stored, shared, and managed.

---

# Question 6: Code Quality & Best Practices

## 6.1 How did you ensure your HTML was valid and error-free?

The HTML was checked by opening the webpage in a web browser and testing its different components.

The following were checked:

- The correct `<!DOCTYPE html>` declaration was used.
- HTML elements were properly opened and closed.
- Elements were correctly nested.
- Attributes were correctly placed.
- Images contained alternative text.
- Navigation links pointed to the correct locations.
- The webpage loaded correctly in the browser.

The code was also reviewed for missing tags, incorrect nesting, and other structural errors.

---

## 6.2 What best practices did you follow for writing clean, readable code?

Several HTML best practices were followed, including:

- Using semantic HTML elements.
- Indenting nested elements.
- Using meaningful IDs.
- Using descriptive headings.
- Adding alternative text to images.
- Organizing related content together.
- Keeping the HTML structure clear.
- Using lowercase HTML tags and attributes.
- Keeping the code properly formatted.
- Using comments where necessary.

These practices make the code easier to read, understand, debug, and maintain.

---

## 6.3 How would you improve your website if you had more time?

If more time were available, the website could be improved by adding CSS to create a more professional and visually appealing design.

JavaScript could also be added to make the website more interactive.

Other possible improvements include:

- Adding a professional profile image.
- Creating a projects section.
- Adding social media links.
- Adding animations.
- Making the contact form fully functional.
- Improving mobile responsiveness.
- Adding more projects.
- Improving the overall navigation and design.

---

# Technical Requirements Checklist

- [X] 25+ different HTML elements used
- [X] 15+ different HTML attributes used
- [X] Semantic HTML structure implemented
- [X] Website works in a web browser
- [X] GitHub repository with all code
- [X] README.md file with documentation
- [X] Instructor added as collaborator
- [X] Instructor followed on GitHub
- [X] Google Classroom submission completed

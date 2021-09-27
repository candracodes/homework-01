# Horiseon SEO Refactoring

## Important URLs

* [Deployed Application URL](https://candracodes.github.io/horiseon-seo-refactoring/) 
* [GitHub Repo URL](https://github.com/candracodes/horiseon-seo-refactoring) 

## Foreword

* This application aims to accomplish the following:
    * Adhere to the [Guidelines](./guide/Homework-Guide/README.md) to ensure submission is in compliance with class standards
    * Ensure that User Story is fulfilled by completing all Acceptance Criteria
    * Application's links all function correctly.
    * Application's CSS selectors and properties are consolidated and organized to follow semantic structure.
    * Application's CSS file is properly commented.
    * Application deployed at live URL.
    * Application loads with no errors.
    * Application GitHub URL submitted.
    * GitHub repository contains application code.
    * Application resembles mock-up provided in the homework instructions (at least 90%).
    * Repository has a unique name.
    * Repository follows best practices for file structure and naming conventions.
    * Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
    * Repository contains multiple descriptive commit messages.
    * Repository contains quality README file with description, screenshot, and link to deployed application.
    * The URL of the deployed application.
    * The URL of the GitHub repository, with a unique name and a README that describes the project.

## Significant Changes Made to Application | HTML

* Title changed from `website` to `Horiseon | Homepage`
* New semantic tags of `header` and `nav` added; removed unneccesary `<div>` with header class
* Comments added for ease of understanding and explanation for future dev team members
* Made hero a section rather than a div
* Replaced benefits div with an article/sidebar element
* Removed excessive benefit classes in exchange for individual sections within the article
* Replaced footer div with semantic footer tag
* Alt tags added to all images and links
* Hover action added to all anchors for intuitive human/computer interaction
* Added flexbox for main content area


## Significant Changes Made to Application | CSS

* Table of contents comments added
* class `.header` removed since `<header>` was implemented into the HTML instead
* `header` added as global semantic element rather than a class type
* `nav` added as semantic element
* Added a class called `back-to-top` so users don't have to scroll all the way to the top from being at the bottom of the page

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Mock-Up

The following image shows the web application's expected appearance and functionality:

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./assets/images/01-mockup-image.png)

## Licensing
The project is made possible with the following Licensing:
- [MIT](license.txt)

## Contact Developer
For additional information, contact this application's developer: letschat@candracodes.com
# Lab 5

This is a simple modified webpage to emphasize the use of accessibility features.

## Getting Started

To get started, clone this repository and run the following commands:

```bash
npm install
```
This will install the necessary dependencies for the project.

## Development

It is recommended to use the VSCode Live Server extension to run the project
locally. This will allow you to see changes in real-time as you make them. There
is no need to run a build process or refresh the page manually. Additionally,
you do not need to setup a local server to run the project.

## Testing

There are no tests for this assignment.

## Accessibility Lab Answers

Color:
When testing the current color scheme using Lighthouse, the color contrast ratio is not sufficient for most elements on the site (article, div.nav, font, html, a, etc.).

Semantic HTML:
1. When trying to navigate the content using a keyboard, I can use the arrow keys to scroll down and I can use the tab key to iterate through navigation buttons, links, search bar, audio widgets, forms and settings. I can also use the enter button to make selections and the escape button to go back or deselect a list. The navigation buttons and search bar do not work when trying to use the enter key.
2. I updated the article text by taking out the breaks and putting each section of text in a paragraph so it is easier for screen reader users to navigate.
3. The navigation menu part of the site should be put in the proper HTML semantic "nav" tag.

The Images:
Added screen reader user access by adding [alt] attributes.

The Audio Player:
1. An accessible alternative for deaf/hard of hearing users is an audio transcript.
2. Those using an older browser can access the audio through the alternate object/embed tag. This will attempt to load the audio in a different way. If this doesn't work, I have included a link to download the audio.

The Forms:
I added a label to each input element and added a class for the label that shouldn't be viewed. I updated the css rule for this specific class so the opacity is 0 and it is not visible.

The Show/Hide Comment Control:
I changed the show/hide div tag to a button tag.

The Table:
I emphasized the column and row titles with the <th> tag and added scope so they could be denoted as rows and columns.

Other Considerations:
1. Add a lang attribute to the html section so the screen reader knows what language the site is in.
2. Add more padding around certain titles to make them easier to read.

## Sources
Readings and W3 Schools website.


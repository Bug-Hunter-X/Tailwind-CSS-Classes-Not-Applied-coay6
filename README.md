# Tailwind CSS Classes Not Applied

This repository demonstrates a bug where Tailwind CSS classes are not being applied to HTML elements, even though the CSS is included and the classes are correctly written.

## Bug Description
The issue involves a simple HTML file with Tailwind classes that do not produce the expected styling. This is unexpected, as Tailwind's CDN is used, and the classes appear to be correctly implemented.

## Setup
1.  Clone this repository.
2.  Open `index.html` in a web browser.

## Steps to reproduce
1.  The `index.html` file contains a div element with the class `bg-red-500`. This class should create a red background.
2.  Observe that the div does not have a red background as expected.

## Solution
The solution involves specifying the content paths in the `tailwind.config.js` file. This ensures that Tailwind knows where to find your HTML files to apply the styles. The updated files are included in the `solution` branch.

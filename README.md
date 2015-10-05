# Design Sprints
This README outlines the details for collaborating on Design Sprints.

## Contributing or Editing Content
For most edits or contributions, please create an issue with the following details:
* The context (the content you want to edit, or where the addition is going)
* The problem you're solving
* The solution to that problem

However, if you feel comfortable enough to make direct edits and submit a pull request, please do. Just be sure to include details on the problem you're trying to solve.

## Editing Pages
In order to locally test each page
* delete the `<base>` tag at the top of every page
* add `../` to the `href=""` in `<link href="styles.css" media="screen" rel="stylesheet" type="text/css">` at the top of each page except for design-sprints/index.html
* add `../` to the `src=""` in `<script type="text/javascript" src="scripts.js"></script>` at the top of each page except for design-sprints/index.html
* before pushing your changes please revert the last three changes

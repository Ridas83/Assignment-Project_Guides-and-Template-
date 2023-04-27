## Summary (Summarize the bug encountered concisely)

When the user navigates to the projects on the site, the link on the page and click on the "New project" button
where it should be possible to create a Blank Project, incorrectly reads "Create Black Project"

## Steps to reproduce

Go to the GitLab site and login to account.
Click on the "Projects" menu option in the navigation bar.
Click on the "New project" button.
The user will see the option Create Black Project

## Example Project

## What is the current bug behavior?

The link/button on the "Projects" page that should read "Create Blank Project" reads "Create Black Project" instead.

## What is the expected correct behavior?

The link/button on the "Projects" page should read "Create Blank Project".

## Relevant logs and/or screenshots

Bug_Project_create_blank.png

## Possible fixes

The text on the link/button should be changed from "Black Project" to "Blank Project"

## Whom do you report/ Assign To/ Tags

/label ~bug ~reproduced ~needs-investigation /cc @project-manager /assign @qa-tester

## Priority

Major

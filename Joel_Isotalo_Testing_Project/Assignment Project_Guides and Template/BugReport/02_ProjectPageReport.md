
## Summary (Summarize the bug encountered concisely)

    Typographical error on the create new project page in GitLab. Instead of 'Create blank project', page shows 'Create black project'.

## Steps to reproduce     
    1. Log in to GitLab with valid credentials
    2. Navigate to URL https://gitlab.com/dashboard/projects
    3. Select 'New project'
    4. Typographical error can be seen on the page

## What is the current bug behavior?

    The selection for creating a new blank project incorrectly shows text 'Create black project'.

## What is the expected correct behavior?

    The selection should show text 'Create blank project'.
     
## Relevant logs and/or screenshots

    Check either the 'image.png' file in this folder or alternatively the link https://i.imgur.com/UstQDRU.png

## Possible fixes

    Page source code should be corrected to display 'blank' instead of 'black' in the selection element.

## Whom do you report/ Assign To/ Tags

    /label ~bug ~reproduced ~needs-investigation 
    /cc @project-manager 
    /assign @qa-tester

## Priority

    Medium-High. This error does not affect the functionality of the page, but it could be confusing/unprofessional and cause reputational damage.

    Source: https://www.testdevlab.com/blog/why-typos-should-be-high-priority-bugs
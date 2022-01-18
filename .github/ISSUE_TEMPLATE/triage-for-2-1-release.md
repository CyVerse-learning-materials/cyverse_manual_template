---
name: Triage for Release
about: Describe this issue template's purpose here.
title: Triage for [Project Title] Release [X.X.X]
labels: 2.1 Release
assignees: ''

---

This is a checklist issue. As we review each repo we should check the following
items.

### 1. Check on file versions (all files below should have a version comment in the first line of the file)

- [ ] `.github/workflows/main.yml` is version 2.1
- [ ] `mkdocs.yml` is version 2.1
- [ ] `requirements.txt` is version 2.1
- [ ] `README.md` is version 2.1
- [ ] `docs/javascripts/intercom-learning.js` is present

### 2. Check on the following required formatting for all pages

- [ ] Documentation contains maintainer info on `index.md` or the appropriate
  first page

    ```
    Manual Maintainer(s)
    --------------------

    Who to contact if this manual needs fixing. You can also email
    <tutorials@cyverse.org>

    | Maintainer | Institution | Contact |
    |------------|-------------|---------|
    | Your Name | CyVerse | <yourname@email.com> |

    ```

- [ ]  Documentation contains the fix/improve instructions on all `.md` pages

    ```
    **Fix or improve this documentation**

    - Search for an answer:
       [CyVerse Learning Center](https://learning.cyverse.org)
    - Ask us for help:
      click [Intercom]() icon on the lower right-hand side of the page
    - Report an issue or submit a change:
      [Github Repo Link]()
    - Send feedback: <Tutorials@CyVerse.org>
    ```

- [ ] All hyperlinks in documentation are updated for the repository

### 3. Overall quality  

- [ ] Maintainer is assigned and has approved the content
- [ ] Editor has checked for quality (spelling, formatting, etc.)
- [ ] Sample/test data is available with anonymous/public read access
      in the appropriate directory at `/iplant/home/shared/cyverse_training`

## About

just use `${{steps.repo-stars.outputs.stars}}` to get repo's star-count.

### Example

```yml
...

on:
  # Triggers the workflow on push or pull request events but only for the master branch
  watch:
    action: started

steps:
- name: Star Count
  id: repo-stars
  uses: alanhg/repo-star-count-action@master

...

```

## About

just use `${{steps.repo-stars.outputs.stars}}` to get repo's star-count.

### Example

```yml
...

steps:
- name: Star Count
  id: repo-stars
  uses: alanhg/repo-star-count-action@master

...

```

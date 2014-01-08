# Engineering Performance Rubric

This is the home of HubSpot's Engineering Performance Rubric.

### Hosting

The rubric is a Jekyll site, which makes it easy to host on GitHub Pages. More information can be found [here](https://help.github.com/articles/using-jekyll-with-pages).

### Editing

Each yaml file inside the `_data` folder defines a category inside the rubric. A category contains:
 - overall qualities (i.e. what does attitude entail?)
 - specific examples for each rubric level (i.e. attitude level 1 == avoids taking reponsibility, etc.)

### Example
This is an example of a yaml file that would exist in the `_data` folder:
```yaml
category: Attitude

qualities:
  - effort
  - ownership
  - helping & kindness

rubric:
  1:
    - stays clear from owning projects, avoids taking responsibility

  2:
    - owns few projects

  3:
    - owns some projects, requires some direction to move them forward

  4:
    - proactively takes ownership

  5:
    - comes up with new ideas, sees them implemented, encourages adoption and contributions
```

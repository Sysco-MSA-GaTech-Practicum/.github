# Sysco & Georgia Tech MSc Analytics Practicum
Our project and practicum Home Page.

## Housekeeping & Setup
Be sure to go through this section before continueing with anything else.


### NDA
[Download Here](https://drive.google.com/file/d/1eo_ZPF-mYmzVnSlCstSVyOqshNQhGOnu/view?usp=drive_link) then please sign and email me the copy at **rodd.talebi@sysco.com**.


### Python & Conda
Let's try to keep the conda environment uniform across all users by regularly updating the `requirements.txt` file as we install new packages.

```
conda create --name sysco --file requirements.txt python=3.7 -c conda-forge # remove '-c conda-forge' if it errors
```

Other helpful conda commans:
* launch a python environment `conda activate [env_name]`
* end the environment `conda deactivate`
* list all packages/modules in the environment `conda list --explicit`
* remove an environment `conda remove -n [env_name] --all`


### Project Management
We will be using the [ZenHub Chrome Extension](https://chromewebstore.google.com/detail/zenhub-for-github/ogcgkffhplmphkaahpmffcafajaocjbd?hl=en-US) for project management. It would be good to start to familiarize yourselves with project management concepts like a [kanban board](https://www.atlassian.com/agile/kanban); here is a [list of other common terms](https://www.indeed.com/career-advice/career-development/management-terms).


### Branch Management
We want our branches to reflect our project organization with respect to epochs and issues. The `main` branch should be protected and should only get `stable` code. Each epoch should get it's own `stable` brach as well like `[epochname]_stable`. And then each issue should get it's own branch following the convention `[epochname]/Issue[###]-[issue_name]`. Regular issues, regular branching, and regular merges will help keep us organized (if used correctly!).


### Group Chat
See GroupMe



## 2024 Practicum

### Data
Released when all turn in their NDA.


### Problem Statement


### Goals


### Deliverables



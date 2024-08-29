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


## *Good to Know* Stuff

**NOTE** most of the links I use below are just the first things the pop up after I google something; I'm not necessarily vouching for these as the best way to learn the material but rather something that looks good enough at a glance.

* git
  * [git vs cloud-hosting-platform like GitHub](https://www.theserverside.com/video/Git-vs-GitHub-What-is-the-difference-between-them)
  * what else is out there that can be used in place of GitHub:
    * GitLab
    * Bitbucket (part of Atlassian suite of products)
* text editors
* basic linux commands
* conda
* object oriented programming
* Atlassian products + Microsoft products
  * Your company will be very likely using one or both of these other companies to get access to some or a lot of their products that are supposed to make working easier or more organized
  * [Atlassian](https://contegix.com/blog/guide-atlassian-product-suite) examples:
    * Bitbucket: like GitHub but not publicly accessible
    * Confluence: a place to make documents that are accessible to everyone (good place to put official documentation for projects, or internal guides/memos, etc) ...kinda like a Google Drive too
    * Jira: has a bunch of project management tools that can link to Bitbucket and the software that is being developed
    * Trello: honestly, basically the same thing has Jira but I guess is not as geared towards software development as Jira...it was it's own thing company until Atlassian aquired it in 2017
  * [Microsoft](https://icplan.com/office-365-a-definitive-guide-to-microsofts-enterprise-offerings/) examples:
    * of course we all know of the basics like Word, Excel, Outlook etc
    * Teams: chat + video call service like Slack
    * SharePoint: basically their GoogleDrive but with an emphasis on files that you want to work with other people on
    * OneDrive: basically their GoogleDrive but with an emphasis on just cloud PERSONAL storage (as oposed to editing on the cloud for everyone to participate in)
* Cloud computing (AWS, GCP, Azure)



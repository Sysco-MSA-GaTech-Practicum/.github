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
  * [cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf) of commands
  * [git vs cloud-hosting-platform like GitHub](https://www.theserverside.com/video/Git-vs-GitHub-What-is-the-difference-between-them)
  * what else is out there that can be used in place of GitHub:
    * GitLab
    * Bitbucket (part of Atlassian suite of products)
* Interated Development Environment or IDE:
  * if we're not being pretentious, IDEs are basically just fancy text editors
  * [VSCode](https://code.visualstudio.com/docs/python/python-quick-start) (most popular)
  * PyCharm
  * Sublime (apparently 'so 8 years ago')
* basic linux commands
  * [cheat sheet](https://www.geeksforgeeks.org/linux-commands-cheat-sheet/) of commands
  * some tl;dr for operating systems (OS):
    * Linux is a FREE! and OPEN SOURCED! OS that is based off Unix which is proprietary/not-free. Because it is open-sourced, it is a favorite amoungst software people who want the freedom to customize and build how they please; as you get deeper into the world of neural networks and GPU-based computations, linux will be the go-to OS especially for the Cloud too. The down-side to being open-sourced are all the different versions (AKA distributions) of Linux that are out there (Ubuntu, Debian, Fedora, CentOS, and Kali Linux for my hackers out there) and also their relative instability.
    * Apple computers have the macOS which was originally built off of Unix as well.
    * Both Linux OSs and macOS give you the ability to open a `terminal` and it will provide access to the Unix command line shell...I think technically it's Unix commands but it's basically universally reffered to as just linux commands...getting really in the semantics here. Apple computers are a close 2nd favorite to software people because it is so similar to Linux so installing and running software is easier. The downside to Apple computers is that they use their own GPUs and not NVIDIA's so you can't use the GPU for training NNs with TensorFlow or PyTorch which need CUDA; and the only reason neural networks became popular (never forget that NNs are a product of the mid-1900s and NOT the 2000s) was because NVIDIA came out with CUDA software for their GPUs that made training NNs scalable/faster.
    * Microsoft's Windows OS is not based off Unix and is it's own thing which makes it a pain in the ass for software people. But since it is way cheaper and accessible than Apple computers, and more user-friendly than Linux distributions, most of the world's companies will use a computer with Windows OS. To play with linxu commands on Windows, try downloading [git bash](https://git-scm.com/downloads) which will open a terminal similar to that in macOS or Linux OS and also makes using command-line git easy to use.
* conda
  * [cheat sheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf) of commands
  * what are [conda channels](https://docs.conda.io/projects/conda/en/latest/user-guide/concepts/channels.html)
  * [conda vs venv](https://vinayak-hegde.medium.com/choosing-between-venv-and-conda-fc60fcc89712) as 2 different ways to make a python virtual environment (venv is built-in with python software which is a plus)
  * [conda vs pip](https://www.reddit.com/r/Python/comments/w564g0/can_anyone_explain_the_differences_of_conda_vs_pip/) ...tl;dr they are not the same thing but still related
* object oriented programming
  * [Youtube Playlist](https://www.youtube.com/playlist?list=PL-osiE80TeTsqhIuOqKhwlXsIBIdSeYtc)
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
* Python packages for NNs:
  * TensorFlow (Google), PyTorch (Facebook), Keras (some dude) are the big 3 and all are open-sourced I'm pretty sure.
  * I want to say that Keras was made to work 'on top of' either TensorFlow or PyTorch, and was made to 'simplify' the process
  * The public and TensorFlow liked Keras so much, that TensorFlow basically adopted it as it's official v2.0 launch of the codebase, so you can think of them as the same now...I guess
  * PyTorch is still around but I see it more in scientific/research community and less in business world; I think because TensorFlow has good tools to make your model 'useable' in applications via [TFX and TF Serving](https://www.tensorflow.org/tfx/guide/serving)
  * TF.keras offers to APIs:
    * Sequential API: for your baby-programmers with basic 'linear' models (input -> layer0 -> layer1 -> ... -> layerN -> done); very simple but that also means minimal customization
    * Functional API: high flexibility, high customization
* Cloud computing (AWS, GCP, Azure):
  * TBD
  * what kind of things do you want to know?



# Abra-Collaboratory

<img align="left" src="resources/AbraCollaboratoryQR.png" width="100" height="100">

<img src="https://img.shields.io/badge/ReproducibleResearch-AbraCollaboratory-magenta.svg?style=plastic" alt="git-AbraCollaboratory">

<a href="https://doi.org/10.5281/zenodo.2851983"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.2851983.svg" alt="DOI"></a>

This repository documents our attempt to leverage native GitHub functionality to conduct reproducible research platform. Why GitHub? Honestly, because it's well-suited for out-of-the-box use as a reproducible research repository.

If you are a new GitHub user and/or if you'd like to better understand how we leverage GitHub tools for reproducible research, we recommend that you start by reading our [Tutorial](../../wiki/Using-GitHub-as-a-Reproducible-Research-Platform).

We are also in the process of drafting some simple GitHub Reproducible Research (GRR) [guidelines](../../wiki/Our-Reproducible-Repository-Guidelines-%F0%9F%98%83). Please take a look and [let us know what you think](../../issues/new?assignees=callahantiff&labels=wiki&template=wiki.md&title=Wiki%3A+Briefly+describe+task).

Let us know if you decide to use this framework, we'd love to feature you as a collaborator on our [wiki](../../wiki) and hear more about how you implemented this framework within your research. We also encourage you to keep the Abra-Collaboratory badge (shown above) on your repo as an indicator of your intent to conduct reproducible research.

### Project Stats

![GitHub contributors](https://img.shields.io/github/contributors/callahantiff/Abra-Collaboratory.svg?color=yellow&style=flat-square) ![Github all releases](https://img.shields.io/github/downloads/callahantiff/Abra-Collaboratory/total.svg?color=dodgerblue&style=flat-square)

<br>

## Getting Started  
Please note that we are working on automating the process of settting up a new reproducible research project. In the meantime, follow the instructions below.

To get started, please follow the steps listed below:
* [Fork the Project Repository](#fork-the-project-repository)
* [Fork the Project Wiki](#fork-the-project-wiki)
* [Update hyperlinks](#update-hyperlinks)  
* [Add Projects Boards](#add-projects-boards)
* [Enable Issues and Verify Issue Templates Transfer](#enable-issues-and-verify-issue-templates-transfer)
* [Invite Collaborators](#invite-collaborators)


### Fork the Project Repository

- From this project, fork the repository by clicking the "Fork" button in the upper right hand corner, as shown below.

<img src="resources/documentation/images/wiki/forking.png">

- Once forked, move to the directory where you would like to download clone your fork so you have a copy locally.
```bash
$ git clone https://github.com/{username}/Abra-Collaboratory.git
```

<br>

### Fork the Project Wiki
- "Fork" the wiki by cloning the original into your local "Abra-Collaboratory" directory.

```bash
$ git clone https://github.com/callahantiff/Abra-Collaboratory.wiki.git
Cloning into 'Abra-Collaboratory.wiki'...
remote: Enumerating objects: 47, done.
remote: Counting objects: 100% (47/47), done.
remote: Compressing objects: 100% (45/45), done.
remote: Total 47 (delta 20), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (47/47), done.
```

- Then, go to the Wiki in your forked repository:
<img src="resources/documentation/images/wiki/wiki_clone.png">

- Once you have crated the wiki page, complete the final steps, in the order shown below.
```bash
$ cd Abra-Collaboratory.wiki
$ git fetch
$ git remote add wiki-fork https://github.com/{username}/Abra-Collaboratory.wiki.git
$ git push wiki-fork -f
Counting objects: 93, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (76/76), done.
Writing objects: 100% (93/93), 6.46 MiB | 1.82 MiB/s, done.
Total 93 (delta 16), reused 0 (delta 0)
remote: Resolving deltas: 100% (16/16), done.
To https://github.com/{username}/Abra-Collaboratory.wiki.git
 + 4bba267...599d6ec master -> master (forced update)
```

<br>

### Update Hyperlinks
Once you have forked the repo and the wiki page, you should then make sure that you have updated the following hyperlinks:
- _Wiki: To Do List_ — update all hyperlinks on this page to the appropriate board in your repo
- _Wiki: Project Meetings_ — hyperlink should point to the meetings project in your repor

<br>

### Add Projects Boards 
Unfortunately, there is not yet a way to clone GitHub Projects boards. That being said, there is still a way that you can access this information and add it to your rerpository. In order to do this, complete the following steps (as shown in the screenshot below):
  1. Go to the "Abra-Collaboratory" [Projects boards](../../projects)
  2. Click and open each board and navigate to the "Menu" as shown below
  3. Inside the "Menu", click on "Copy"
  4. Select the dropdown and find your "{username}/Abra-Collaboratory"
  5. Verify the checkbox to include "Automation settings" is checked
  6. Remove "[COPY]" from the Project board name textbox

Once you have performed these steps, push the green button and copy the copy. Repeat these steps for each of the four "Abra-Collaboratory" Projects boards.

<img src="resources/documentation/images/wiki/git_projects.png">

<br>

### Enable Issues and Verify Issue Templates Transfer

By default, cloned repositories do not have the Issues feature enabled. In order to allow creation of issues, go to the "Settings" page for your repository:

<img src="resources/documentation/images/wiki/settings.png">

Scroll down to the "Features" section and check the box next to "Issues":

<img src="resources/documentation/images/wiki/features_issues.png">

If you correctly cloned the "Abra-Collaboratory" repository, you should see the follow documents in your project homepage:

<img src="resources/documentation/images/wiki/cloned_repo.png">

***

<br>

### Invite Collaborators
Now that you have cloned the repository, wiki, have copied the project boards, and verified the issue templates, you are ready to customize the repo for your project. At this point we recommend that you update the README and Wiki homepage to describe your project.

You are now ready to invite your collaborators! To make this process easier, we have written a template email, which you will find [here](../../blob/master/resources/New_Collaborators_Invitation_Email.md). To use this template, update the slots denoted with "{}" and navigate to the "Preview Button". At that point, you should see something similar to the image shown below. From the "Preview", copy and paste the text directly into an email.

<img src="resources/documentation/images/wiki/collaborator-email.png">

_____

Return to [Menu](#getting-started)

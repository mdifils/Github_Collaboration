# Github Collaboration

## Description
The main goal of this project is to learn how to collaborate on the same project
using Git and Github.  
We will be covering the following topics:
- [How to initialize a new repository and invite people to contribute to our project](#initialization)
- [How to contribute to a project](#contributions)
- [How to create a version of our project](#versionning)

---
## Initialization
1. Create a GitHub repository with a README file.
2. Clone your repository on your computer : `git clone <your repository-github-link>`
3. Move into your repository directory: `cd <your-repo-name>`
3. Create a new branch "development" and Go to that new branch : `git checkout -b development`
4. Write 3 lines of texts in the README file.
5. Add the file to the staging index : `git add README.md`
6. Save the state of the file by making a commit : `git commit -m "your-message"`
7. Push the branch "development" : `git push -u origin development`
8. Invite your colleagues as contributors (watch the video below)

[![Add collaborators](https://img.youtube.com/vi/p49LRx3hYI8/0.jpg)](https://www.youtube.com/watch?v=p49LRx3hYI8)

---
## Contributions
1. Go to a repository where you have been invited
2. Make a clone
3. List the existing branches: `git branch -a`
4. Go to the "development" branch: `git checkout development`
5. create a branch called your-name from there: `git checkout -b <your-name>`
6. Open README file on your favorite text editor (e.g: VScode): `code README.md`
7. Add 3 lines at the end of the file.
8. Add the file to the staging index : `git add README.md`
9. Save the state of the file by making a commit : `git commit -m "your-message"`
10. Go back to the development branch: `git checkout development`
11. Merge "your-name" branch with "development" branch: `git merge <your-name>`
12. Push the "development" branch: `git push -u origin development`
13. Delete the branch "your-name": `git branch -d <your-name>`
14. Repeat the 13 last steps for all the invitations you received.

---
## Versionning
1. When all your colleagues have pushed to your repo, return to your deposit
2. Make a merge of "development" on "main"
3. Make a "main" tag named "version-1"
---

## Collaboration

I am a junior developer at BeCode.  
I have just started my training as an DevOps Engineer.  
I have met new friends and the name of our promotion is LoveLace 8.

Below my colleagues are going to complete the missing part of the story:  
---
 jose
 Dev
 L'ineluctable
---
Hi jose, very nice and straightforward work. well done! 
Kind regards, Rein.

 Dev career  comming soon :alien: 
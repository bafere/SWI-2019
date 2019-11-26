# SWI 2019 (/2020)

## SWI 1

These are materials for the [Software Engineering 1](http://is.mendelu.cz/katalog/syllabus.pl?kod=PEF:SWI1) course,
Tuesday group, 11am local time, even-numbered weeks, taught on Mendel University in Brno, fall 2019, led by [@ZitaNemeckova](https://github.com/ZitaNemeckova) and [@himdel](https://github.com/himdel).

The topic will be Git, the whole semester.

If you need to contact us, please use the [ManageIQ/welcome](https://gitter.im/ManageIQ/welcome) channel on [Gitter](https://gitter.im). (You'll need a github login anyway.)  
Feel free to use that channel to share anything useful you've found :).


### Synopsis:

| date | topic |
|-|-|
| 2019-10-01 | Intro @ Red Hat |
| 2019-10-15 | (dekanske volno) |
| 2019-10-29 | Basics recap, Github, get it working |
| 2019-11-12 | Synchronization, Conflicts |
| 2019-11-26 | Rebase, graded exercise |
| 2019-12-10 | Advanced git |


#### 2019-10-15 (homework :))

Check out https://learngitbranching.js.org/ , go through the whole Introduction Sequence in the Main section, and look at the first Push & Pull exercise in the Remote section.
You can also try for yourself at http://git-school.github.io/visualizing-git/#free .


#### 2019-10-29 - Basics recap, Github, get it working

1. Recap of the git branching exercises

1. Make sure you have a github account, quick intro to github if needed

1. Get git working on your machines, make sure you can push to github

1. History, the why, what?  
  - `git log` - show what's what

5. Basics - `init`/`clone`, `git config`  
  - commits
  - branches
  - exercises, see below


#### 2019-11-12 - Synchronization, Conflicts

1. remotes

1. updating (pull vs fetch & merge...)

1. Conflicts  
  - branches (continued)
  - merge

1. `filter-tree`


#### 2019-11-26 - Rebase, graded exercise

1. rebase flow

1. `git rebase -i` - more real examples, get to try everything


#### 2019-12-10 - Advanced git

1. aliases, scripting, more configuration, .git directory structure


### Exercises

- Basics (2019-10-29)
  - Install some text editor if you don't like vim/nano
  - Set git username and email
  - Add a ssh key to your GitHub account
  - Fork [the SWI-2019 repository](https://github.com/RoadToSoftwareFactory/SWI-2019)
  - Clone the repository
  - Set up remotes
  - Create new branch
  - Create a file `<github login>/commit.md` inside the repository
  - Add some text to the file and create 1st commit
  - Add the hash of the 1st commit to the file and create 2nd commit
  - Add another line of text to the file, then add diff to the file and create 3rd commit
  - Create a pull request to the upstream repository


- Synchronization (3rd class)
Everybody open the file git-rebase.

Read the instructions carefully please :).

Every instruction should be one commit (this time).

  * so your first commit would just be deleting a line
  * and your second commit would change the other line
  * and so on :)

---

After you're done there..

1. Create a PR.

1. You should have a PR with 8 commits, **not** on your master branch - if not, try again :).

1. tell us - wait for a conflict

1. update your branch & resolve conflicts

1. reorder commits so that food-related commits are together

1. squash food-related commits into one

1. delete commit with your favorite color

1. rename commit with your favorite season to something in UPERCASE

1. edit commit with your favority city so it's Helsinki

---

## **EXAM**

Remember to read instructions from Git. It will tell you what to do :)

Update your master.

Everybody open the file `exam`. 

Read the instructions carefully please :). Use your notes or Google as much as you want. But do not talk with your classmates please.

Please switch to a new branch. 

Every line should be one commit (this time).

  * so your first commit would just be changing a line
  * and your second commit would change the other line
  * and rest is yes/no questions - one per commit


---

After you're done there..

1. Create a PR.

1. You should have a PR with 10 commits, **not** on your master branch - if not, try again :).

1. tell us - wait for a conflict

1. update your branch & resolve conflicts (hint: rebase) (20%)

1. reorder commits so that `next class`-related commits(questions 3, 5, 7) are together (10%)

1. squash `next class`-related commits into one (hint: you should use two `s` not three) (20%)

1. delete commit with question 1 (10%)

1. rename commits about your previous experience with Git (questions 2, 4) to be in UPERCASE (hint: you do not rename the commit at the same time as you write `r` but later) (20%)

1. edit commit that mentions SVN so answer is `Noooooooooooo` or `Yesssssssssss` (hint: you have to add changed file and amend commit) (20%)

1. push (with `-f`orce) and check it's ok (you should have 7 commits)

1. When done comment on your PR with something like `please review @himdel` or `please review @ZitaNemeckova`
  
---

The course will be followed by [Software Engineering 2](https://is.mendelu.cz/katalog/syllabus.pl?kod=PEF:SWI2).  
Details to be determined.

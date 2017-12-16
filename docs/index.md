# Course Scaffold

This is the scaffolding project for many labs and assignments.

This project is preconfigured with all of the necessary files to submit the assignments and get them to successfully build on [TravisCI](https://travis-ci.org)

Every assignment will require you to create a new [branch](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging) e.g.

```bash
git checkout -b hello-class
```

and modify the [.travis.yml](https://docs.travis-ci.com/user/customizing-the-build/) file. 

Additionally, your work will be graded using [test automation](https://en.wikipedia.org/wiki/Test_automation) and the [pytest](https://docs.pytest.org/en/latest/) module.

# Getting Started
In order to get started with the hello-class assignment, please complete the following steps.

## Step 1
Install [Anaconda Python](https://anaconda.org/) or any other python distribution you prefer and create a **Python 3.x** virtual environment.

[For instance](https://conda.io/docs/user-guide/tasks/manage-python.html)

```
conda create -n py36 python=3.6 anaconda
```

## Step 2
Install [Git](https://git-scm.com/), sign up for [GitHub](https://github.com/), and follow the [instructions](https://help.github.com/articles/connecting-to-github-with-ssh/) on how to upload your SSH Keys.

## Step 3
Click the Github Classroom Link associated with this assignment located in your universities learning management system (e.g. Canvas, BlackBoard, Desire2Learn, etc.).

## Step 4
Clone the generated repository locally.
```
git clone
```

## Step 5
Checkout the branch for the 1st assignment
```bash
git checkout hello-class
```

## Step 6
Follow the instructions in the README.md within the hello-class branch.

## Other notes

* You'll submit all future assignments using this method so it's critical that you understand these steps.
* [TravisCI](https://travis-ci.org/) is a [continous integration](https://en.wikipedia.org/wiki/Travis_CI) service that allows us to build and validate our code immediately upon pushing to to GitHub. In doing so, I'll be able to periodically reivew your build status (Pass / Fail) and more easily help debug and grade your assignments. Projects must __pass the build__ to be considered in grading. Any project that __fails to build__ at the time of grading will not receive any credit for the assignment.
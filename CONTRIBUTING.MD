# Contributing to Social Media CLone

This document goes over how you will build your project.

## Time Tracking

It is important that you log how much time you spend working on this project. If you don't accurately log time, you will not get credit for this experience.

For Self-Learning, time spent should be included in your response to the weekly discussions.
For Issues, the 

## Self Learning

Every week, a discussion post will be opened titled `Learning (Week MM/DD/YYYY)`.
Anything you research for this project should be logged here.

You should respond the post each week. Your post should contain:
- A description of what you learned and how it can be used
- A link to videos or articles that you used in case others want to learn the same thing
- How much time you spent learning, including watching/reading the video/article as well as any testing you did on your own by writing some code.

## Project Work

We will be using git for version control in order to collaboratively build this application.
Git allows multiple users to work on multiple files (or even the same file) and merge the changes at a later point.
I've outlined our workflow below:

### Step 1 - Creating an Issue

Before we start doing any work, we want to create an "issue" to track the work. This can be done in GitHub in the *Issues* tab at the top.

1. Click the *New Issue* button
2. Add a title and description. All the basic requirements for the feature or fix should be laid out in this issue.
3. Add some labels
   - If you've found a bug, add the *bug* label
   - If you're creating a completely new feature, add the *enhancement* label
4. If you play on working on this issue on your own, click *Assign yourself* under the *Assignees* tab on the right.
5. Click *Create* at the bottom

### Step 2 - Create a Branch

GitHub uses a branch structure to track file changes. The main branch is the current version of our application.
Any other branches are for developing new changes. When we finish developing a feature or bugfix, we can then merge that branch into the main branch via a Pull Request. I'll explain more about that later.

When a new feature is being added, we create a new branch for that specific feature.

Although branches can be named anything, it's best to follow a convention.
We will use the following format for our branch names: `issue-[issue #]/[3-5 word summary of issue]`

Make sure to replace whats in the square brackets with what they're asking for.
You can get your Issue number by looking at the issue you created earlier and the summary can be whatever you want, but try and make it useful.

### Step 3 - Making Changes

In the IDE of your choice, make your changes. When you're done, your IDE should have a system for commiting your changes to git.

When we make a commit, we will follow the following format: `[feat or fix]: [description]`

feat* represents a feature and *fix* represents a bugfix. The description should briefly explain the work you did in this commit.
You may have multiple commits in a branch and its recommended that you do so. For example, you might have a commit to create the feature, followed by another commit to fix a bug with that feature, then another commit adding more to the feature.

### Step 4 - Pushing Changes

Once your changes have been made, you need to upload them to GitHub. This process is called pushing.
There should be an option in your IDE to push or sync with git. It may also show as a publish branch button the first time you upload your changes for a branch.

### Step 5 - Pull Request

Once your branch is pushed, you must create a pull request.

We do not give you permission to push directly to main. Instead, all work must be placed in a pull request.
A pull request is a way to request that your work from a branch gets merged into the main branch.
To create your pull request:

1. Go to the GitHub and select the *Pull requests* tab
2. Click *New pull request* at the top right
3. For the base branch select *main*
4. For the compare branch select the branch you want to merge
5. Set the title as the same title as the issue the pull request resolves
6. In the description, type `resolves #[issue #]` to link the pull request to the issue
7. Click the create button

### Step 6 - Merge

Once your pull request has been approved, it can be merged into main. This will make the code part of application.


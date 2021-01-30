# safaridocs
GIT Fundamentals by Brent laster
Repo for safari labs and related docs



If you design, create, or test software or manage any part of a software development lifecycle, chances are that you’ve heard of Git—and perhaps have tried to use it. When transitioning from another source management system to Git, you’re likely to encounter a few challenges. To overcome them and be most effective, you must first have a clear understanding of the Git model and workflow.

Join Brent Laster to gain the knowledge and skills you need to leverage Git to greatly simplify and speed up managing all of the changes in your source code. Once you understand the fundamentals, Git will grant you a freedom and flexibility that no other source management system can match.
What you'll learn-and how you can apply it

By the end of this course, you'll understand:

    What Git is, the core ideas and overall design behind it.
    Strategies for being able to effectively use Git to simplify source code management and related workflows.

And you will be able to:

    Simplify and speed up managing the changes in your source code.

This training course is for you because...

    You are a developer with code to manage and you need to use a source management tool that empowers you instead of getting in your way.
    You are a manager or project manager with deadlines and need to understand how to access and examine code in a Git repository.
    You are a tester with test cases to manage and you need a way to manage your tests in source control easily.

Prerequisites

    It will be helpful to have a working a knowledge of source control concepts and experience using at least one other source control system.

Before the course:

    Please download and install the appropriate version of Git from the main git website at http://git-scm.org. Ensure that you can run git from the command line. Do this by opening a terminal or emulator session and typing “git --version”. This should return the current version for the revision of Git that you have installed.
    Also, if you do not already have one, sign up on http://github.com for a free account. Note that you do not need a paid account, just a public one to use in the class.

About your instructor

    Brent Laster is a global trainer, author, and speaker on open source technologies as well as an R&D director at a top technology company. He’s been involved in the software industry for more than 25 years, holding various technical and management positions. Brent has always tried to make time to learn and develop both technical and leadership skills and share them with others. He believes that regardless of the topic or technology, there’s no substitute for the excitement and sense of potential that come from providing others with the knowledge they need to accomplish their goals.

Schedule

The timeframes are only estimates and may vary according to how the class is progressing
Day 1

Segment 1 – What is Git? (15 min)

    Instructor will present an overview of Git—what it is, the different packages and interfaces available for using it, and a quick look at some of the overall advantages and challenges of using it over other source control management systems (SCMs).
    Participants will gain an understanding of the basic concepts, choice of interfaces, and potential benefits and challenges of using Git.

Segment 2 – Key Concepts (20 min)

    Instructor will present an overview of the key design concepts behind Git. This includes both the external ones such as the Centralized vs. Distributed repository approach and the internal ones such as the snapshot vs. delta storage method. We will also talk briefly about some design considerations when migrating repositories from other SCMs.
    Participants will gain an understanding of what makes Git different from other SCMs in the way it approaches source management tasks and in how it is used.

Segment 3 – The Git Promotion Model (15 min)

    Instructor will cover the Git Promotion Model, which helps students relate the different levels in Git to a well-known Dev-Test-Prod model.
    Participants will gain an understanding of the levels and overall workflow when working with Git.

Break (10 min)

Segment 4 – Configuration and Setup (20 min)

    Instructor will cover Git command syntax and format, porcelain vs. plumbing commands, auto-complete and basic user configuration and environment setup.
    Participants will learn what they need to know to interact with Git and start working with it.

Segment 5 – Creating repositories (10 min)

    Instructor will explain how to create repositories with Git or clone existing ones. Also we will discuss what is actually in the repositories as far as the underlying structure and content.
    Participants will gain an understanding of the workflow to create a new repository or work with an existing one as well as the underlying structure of a repository.

Segment 6 – Creating Aliases (10 min)

    Instructor will show how you can create aliases in Git as an extension of configuration.
    Participants will gain an understanding of how to create and use aliases to simplify their interactions with Git.

Segment 7 – Getting Productive (20 min)

    Instructor will explain how to use the Git workflow to put content into Git going through the stages of the promotion model previously discussed. We will also look at how to use the amend functionality to update an existing commit in the repository.
    Participants will gain a clearer understanding of the workflow process for putting content into Git.

Assignment: Creating and exploring a repository and managing content. In this lab, students will create a Git repository and take content from their local directory all the way into the Local Git repository.

Break (10 min)

Assignment time (10 min)

Segment 8 – Status of content through the workflow (15 min)

    Instructor will discuss the different states that content can have while traveling through the Git workflow. Included in this is covering the Git status command and understanding what it tells you and how to use it.
    Participants will understand the different states that content can have in Git as well as how to use the status command.

Segment 9 – Seeing differences in content at different levels (15 min)

    Instructor will discuss how to think about Git’s approach to diffing, the diff command and options and some different interfaces for use in looking at differences in Git.
    Participants will learn how to use the commands and interfaces to see differences in content between the various levels in Git.

Assignment: Tracking Content through the File Status Life Cycle. In this lab, students will use the Git status and diff commands to fully understand a file’s state in Git and the differences as they move content through the levels from their working directory to the local repository.

Assignment time (15 min)
Day 2

Segment 10 – Working with changes over time (25 min)

    Instructor will discuss how to see history in Git, both through command line and visual interfaces, as well as how to tag particular changes, and rollback/undo changes with the Git reset and revert commands.
    Participants will gain an understanding of how to track changes over time in Git and how to mark revisions with tags and reset back to a previous version of content.

Assignment: Working with changes over time and using tags. In this lab, students will explore different ways to use the log command and tags.

Assignment time: 15 min

Break (10 min)

Segment 11 - Local Branches (30 Minutes)

    Lecture: How branching works in Git; operations such as creating and deleting; branching models; what the checkout command really means and does in Git
    Hands-on exercise: Create a new branch and make changes to it to understand how the branching process works in Git

Segment 12 – Merging content (20 min)

    Instructor will discuss how merging works in Git and different merge strategies that Git can use.
    Instructor will discuss similar operations such as rebasing and cherry picking and show how those work.
    Instructor will cover how to deal with merge conflicts including how to use visual tooling to help resolve differences.
    Participants will gain an understanding of the different options available to them for merging content in Git.

Break (10 min)

Segment 13 – Dealing with Merge conflicts (20 min)

    Instructor will discuss what constitutes a merge conflict in Git and available strategies and options for resolving conflicts, including visual merge tools.
    Participants will understand what Git recognizes as a merge conflict and options for resolving them.

Assignment: Practicing with merging. In this lab, students will work through some simple branch merging scenarios.

Assignment time (10 min)

Segment 14 – Supporting files in Git (10 min)

    Instructor will cover the use of the Git Attributes file and the Git Ignore files.
    Participants will gain an understanding of how and when to create and use these important supporting files in their Git repositories.

Segment 15 – Git remotes (20 min)

    Instructor will discuss what Git remote repositories are, how they differ from the local repositories, and how the remote command is used to access them.
    Instructor will cover the workflow used to interact with the remote repositories, including pushing content into them, and fetching and pulling content from them.
    Participants will gain an understanding of how to use and access remote repositories in Git to share their content with others and to interact with others’ content.

Assignment: Using the overall workflow with a remote repository. In this lab, students will see how to take the changes they have been working with and put them into a remote.

Assignment time (10 min)

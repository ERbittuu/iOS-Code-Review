What if I told you that it is really good for a software developer to do daily commits to Git? Many would claim it’s not essential and they prefer to take a few days to “properly” craft a commit.

Programming is an art, and it requires careful coding and merging, right? Why rush and commit frequently?

Wiser developers know that daily commits are extremely important.

The truth is some of the best contributors on Github have daily commits or a high commit frequency.

#### Why are daily commits so valuable? For the following reasons:

    Small PR’s (and commits) are easier to code-review instead of large PR’s
    Small commits contribute to team-work and build trust in the team since the contributions are visible and frequent
    A well-crafted commit is releasable (it enables daily builds)
    A daily commit (and build) delivers business and user value to production users, which is the ultimate purpose of most software development projects
    A daily commit contributes to continuous integration, which can reduce risk of unsuccessful merging and delayed integration of software components
    A daily commit builds a discipline of continuous delivery since it’s a habit of providing value
    Daily commits can be aligned with tasks, subtasks and acceptance criteria, which makes them even more valuable to the team
    Daily builds are one of the few metrics that enable comparison of efficiency between software teams. They are a way to benchmark your team against other teams.


Here is commit message that must be used in every single git commit.

- [config]  any configuration files is changed
- [doc]  if you are updating any documentation files. e.g. README
- [feature]  when we implement any new feature
- [fix]  when we fix any specific bug, try to add github id whenever possible
- [refactor]  when there is no fix nor feature, but we improve code for better performance or standards. e.g. eslint fixes.
- [wip]  only when you are working on a feature/fix and it’s not completed but you have to commit in git.


#### Only use like prefix then two space then your commit message 
Not acceptable:
- [config] any configuration files is changed
- [doc] -if you are updating any documentation files. e.g. README
- [feature]- when we implement any new feature
- [feature] - when we implement any new feature
- [fix]1. when we fix any specific bug, try to add github id whenever possible

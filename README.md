# Docs and Helpers

## New Project Setup

### Git

See link for setting up a new project for the first time:

{% embed url="https://www.atlassian.com/git/tutorials/setting-up-a-repository" %}

Rebase commands for MR
```
git checkout master
git pull
git checkout my-branch-name
git rebase master
// fix any conflicts
git push --force
```

### RSPEC Setup

Create a project directory and also a spec directory in it.

Now run following command to set up rspec  - 

```text
rspec --init
```

{% embed url="https://semaphoreci.com/community/tutorials/getting-started-with-rspec" %}




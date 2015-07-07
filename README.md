# darcy-framework

Collection of darcy projects aggregated as git submodules.

Working with git submodules is not without caveats, please see: http://git-scm.com/book/en/v2/Git-Tools-Submodules

To get started, the simple version is:

```bash
git clone --recursive https://github.com/darcy-framework/darcy-framework.git
git submodule init
git submodule update
```

This will download whatever commit the submodule repo (what you're looking at) has pointed to for each repo. If you want to update to the latest, you can use the individual submodule repo as if they were independent (so `git fetch && git merge` to get the latest) or you can update all submodules from the darcy-framework repo root with `git submodule update --remote`. I will try to keep this repo up to date.

## New to darcy?

Start here! http://darcy-framework.gitbooks.io/automating-applications-with-darcy/

The `combine-git-repos` tool maps git repos into subdirectories of a new git repo, preserving commits. 

This requires that the repo has a remote called origin, that remote's HEAD (usually _master_ or _main_) is then used to create a merge. For simplicity, it is recommended that you use clean new clones of repos you want to combine.

There is example usage of `combine-git-repos` in [example](blob/master/example), and there is a usage docstring in the script itself.
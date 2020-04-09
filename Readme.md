# ENSC 481-1 Computational Dynamics

# Instructions
## Update from instructor's changes
'''
git checkout master # The master branch is associated with his remote
git fetch
git pull
'''
## Merge instructor's changes into my files
'''
git checkout Jackson # Move to my branch that is associated with my remote
git merge master # Merge master INTO my branch
'''
## Push my changes to my remote
'''
git checkout Jackson # my branch
git push
'''
## Notes on remote repos
Master branch tracks instructor's remote, origin
Jackson branch tracks my github remote, myGitHub
To view git urls:
'''
git remote origin --get-url # replace 'origin' with 'myGitHub' for my remote
'''
Make sure when creating any new branches I push to the 'myGitHub' remote!
'''
git checkout -b <myNewBranch>
<make changes>
git  push --set-upstream myGitHub <myNewBranch>
'''


- Examples from class, Spring 2020
- Author T. Fitzgerald

## Sections

### Julia
Some introductory examples of using [Julia](https://julialang.org/) and
[Jupyter](https://jupyter.org/) notebooks.

### Linear Algebra
- Eigenvalues and vectors
- Controls example

## TODO
- lots of stuff

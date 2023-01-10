## How I set up the second project

- Made project by `yarn create next-app` command

- Created `src` dir and moved `pages` and `styles` dir.

- Created `components` dir in `src`

- `cd src`

- Added submodule to the project `git submodule add https://github.com/TOMO-YOSHI/components.git ./components`

## How to commit the submodule
Submodules are not tracked by the git commands at the root dir. Therefore, devs have to run `git add`, `git commit`, and `git push` separately.

## How to pull and update the submodule after the remote repo has been updated
- `git pull --recurse-submodules`

- `git submodule update --remote` 

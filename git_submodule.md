# Git Tools - submodule
Submodules allow you to keep a Git repository as a subdirectory of another Git repository. This lets you clone another repository into your project and keep your commits separate.
[Submodule documentation](https://git-scm.com/book/en/v2/Git-Tools-Submodules)

## Command
- `git clone --recurse-submodules <path>` - Clone including submodules
- `git submodule add <url> <directory>` - Add submodule
- `git submodule update` - Update submodule. `--init` to also initialize
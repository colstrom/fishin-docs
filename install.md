fishin install
==============

Usage
-----

`fishin install <source> <function> [branch]`

`source` is the is the GitHub repository to fetch from using the common <owner>/<repo> format.
`function` is the path to that function within the repository (.fish is appended automatically).
`branch` is the branch name to fetch from (default is master).

Examples
--------

`fishin install colstrom/fishin fishin`

This would install the `fishin` function from the `colstrom/fishin` repository.

`fishin install colstrom/fishin fishin develop`

This would install the `fishin` function from the `develop` branch of the `colstrom/fishin` repository.

`fishin install colstrom/dotfiles .config/fish/functions/fish_prompt`

This would install the `fish_prompt` function found under `.config/fish/functions` in the `colstrom/dotfiles` repository.

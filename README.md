# Absolutely Vishus

The best ever [Starship](https://starship.rs/) theme for a colorful and succinct terminal prompt.

Regular user:

![Regular user prompt for a Rust project with a git repo](absolutely_vishus_user-git-rust.png)

Root user:

![Root user prompt](absolutely_vishus_root.png)

For more examples see the [Screenshot](absolutely_vishus.png)


## Features

Includes support for the following modules out of the box: `character`, `jobs`, `username`, `directory`, `git_status`, and `git_branch`, as well as support for languages.

- **User**
  
  - shows `root` in a bright color when logged in as root

- **Directories**
  
  - replaces common home directories with emojis to shorten prompt length

- **Git**
  
  - displays a circle for modifications
  
  - displays a sad face for conflicts
  
  - displays a symbol for stash and the number of stashes
  
  - displays branch name

- **Errors**
  
  - adds a red `X` if the last command was an error

- **Jobs**
  
  - displays an icon if there are paused jobs

- **Languages**
  
  - easy to customize languages; just change the `style = "..."` line
  
  - custom icon and background for Rust



## Todo

- add customization for others languages

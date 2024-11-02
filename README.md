# git-browse

Opens a page in the browser with the current repository 🔗

> Give a ⭐️ if this project helped you!

## Installation

Clone the project:

```bash
cd ~/projects/ # or any workspace what you use
git clone git@github.com:piecioshka/git-browse.git
```

Add to shell configs:

```bash
# Bash: please add to `~/.bash_profile`
export PATH="$HOME/projects/git-browse/:$PATH"

# Fish: please add to `~/.config/fish/config.fish`
set -gx PATH $HOME/projects/git-browse/ $PATH
```

## Usage

```bash
$ cd git-repository/
$ git browse
$ # Default browser will open repository page!
```

## Aliases

List of aliases, which are available after installation:

- `git open`
- `git www`

## Related

* [git-scripts](https://github.com/piecioshka/git-scripts) - Utilities Git scripts _(mostly in Node.js)_

## License

[The MIT License](https://piecioshka.mit-license.org) @ 2023

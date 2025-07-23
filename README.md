# jj-extra - Jujutsu CLI extra aliases

This plugin provides additinal aliases for [jj](https://jj-vcs.github.io/jj).

To use it, add `jj-extra` to the plugins array of your zshrc file:

```zsh
plugins=(... jj-extra)
```

## Aliases

| Alias  | Command                       |
| ------ | ----------------------------- |
| jjb    | `jj bookmark`                 |
| jjbc   | `jj bookmark create`          |
| jjbd   | `jj bookmark delete`          |
| jjbf   | `jj bookmark forget`          |
| jjbl   | `jj bookmark list`            |
| jjbm   | `jj bookmark move`            |
| jjbr   | `jj bookmark rename`          |
| jjbs   | `jj bookmark set`             |
| jjbt   | `jj bookmark track`           |
| jjbu   | `jj bookmark untrack`         |
| jjgpa  | `jj git push --all`           |
| jjgpd  | `jj git push --deleted`       |
| jjgpt  | `jj git push --tracked`       |
| jjrbm  | `jj rebase -d "trunk()"`      |
| jjst   | `jj status`                   |

## See Also

- [jj-vcs/jj](https://github.com/jj-vcs/jj)

## Contributors

- [imp](https://github.com/imp) - Plugin Author

# tuckr_dotfiles

### Setup env var
```zsh
export TUCKR_HOME=$HOME/Development/tuckr_dotfiles
```

```nu
export-env {$env.TUCKR_HOME = $"( [ $env.HOME 'Development/tuckr_dotfiles' ] | path join)" }
```

### Example symlinking dotfiles.

```
tuckr add ghostty
```

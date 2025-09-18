# dotfiles

[Chezmoi](https://chezmoi.io) enabled repo.

A `~/.config/chezmoi/chezmoi.toml` file is needed to safely clone the files, with these keys:

```toml
[data]
    email = "personal_email@example.com"
    context = "work"  # can be whatever you want, work is the only one with side effects for now
    work_email = "work_email@example.com"
    work_github_org_name = "your_org"
```

## Known issues

At the moment I'm not supporting that well a double github user conf, due to `gh` cli auth issues.


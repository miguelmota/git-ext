# git-ext

> My collection of git extensions and hooks

## Install

```bash
git clone https://github.com/miguelmota/git-ext.git
cd git-ext/
chmod +x extensions/*
sudo cp extensions/* $(git --exec-path)/
```

## Examples

Open git url:

```bash
$ git open
```

Merge a PR:

```bash
$ git pr-merge <number>
```

## License

[MIT](LICENSE)

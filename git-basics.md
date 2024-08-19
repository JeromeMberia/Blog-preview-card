# Basics

## How to write a commit message

```
[type](optional content): [subject]
[optional body]
```

### types

- **build:** Related to build process changes;
- **ci:** Related to continuous integration setup changes;
- **chore:** About build process or auxiliary tool changes;
- **docs:** Limited to documentation changes;
- **feat:** Introducing new features;
- **fix:** Addressing bug fixes;
- **perf:** Enhancing code performance;
- **refactor:** Code changes without bug fixes or new features;
- **revert:** Reverting previous changes;
- **style:** Markup, formatting, or whitespace changes;
- **test:** Adding missing tests.
### Examples
> "feat(api): Add support to create coupons"

**or**

> "chore!: Update Python version to use newer libs
>
> More recent versions of important project libs no longer support Python
> 3.6. This has prevented us from using new features offered by such libs.
> Add support for Python 3.12.
>
> BREAKING CHANGE: drop support for Python 3.6"

### Commands

```shell
git commit -m "My commit message"
```

```shell
git commit -m "My Subject" -m "My description..."
```

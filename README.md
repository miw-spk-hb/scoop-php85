# Scoop PHP 8.5 Bucket

This is a Scoop bucket for easy installation of PHP 8.5 versions on Windows via [Scoop](https://scoop.sh/).

---

## Contents

The bucket currently includes:

- `php853` – PHP 8.5.3

Additional PHP 8.5 versions will be added as needed.

---

## Requirements

- Windows 10 or 11  
- [Scoop](https://scoop.sh/) installed  
- Git (optional, for updating)

---

## Adding the Bucket

Add the bucket to Scoop with:

```powershell
scoop bucket add php85 https://github.com/miw-spk-hb/scoop-php85
```

## Installation of PHP 8.5.x
`scoop install php85x (only available version yet is PHP853)`

## Verify Installation
`php -v`

## Problems?
First try to update scoop
`scoop update` or `scoop update php85`

## Uninstall
simply use `scoop unsintall php85x`

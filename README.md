# pmahomme

A dark theme for [phpMyAdmin](https://www.phpmyadmin.net/), styled after GitHub's dark color palette.

![Theme preview](screen.png)

## Overview

**pmahomme** is the default phpMyAdmin theme. This repository contains a customized dark variant built on GitHub's dark UI colors (`#0d1117` base background, `#6cb6ff` links, `#c9d1d9` text). It is built with SCSS and compiles to a single CSS bundle with RTL support.

## Compatibility

| Theme version | phpMyAdmin versions |
|---|---|
| 5.0 | 5.0, 5.1, 5.2 |

## Installation

1. Copy the `pmahomme` directory into your phpMyAdmin `themes/` folder:

   ```bash
   cp -r pmahomme /path/to/phpmyadmin/themes/
   ```

2. Log in to phpMyAdmin, go to **Settings → Themes**, and select **pmahomme**.

## RTL Support

A precompiled RTL stylesheet is included at `css/theme.rtl.css` for right-to-left language support. phpMyAdmin loads this automatically when the interface language is set to an RTL locale.

## License

This theme follows the same license as phpMyAdmin — [GNU GPL v2 or later](https://www.gnu.org/licenses/gpl-2.0.html).

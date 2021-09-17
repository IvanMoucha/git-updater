![GitHub Updater](./assets/GitHub_Updater_logo_small.png)

# GitHub Updater - 9.x fork

![downloads](https://img.shields.io/github/downloads/IvanMoucha/github-updater/total) ![downloads@latest](https://img.shields.io/github/downloads/IvanMoucha/github-updater/latest/total)

![WordPress Tests](https://github.com/IvanMoucha/github-updater/workflows/WordPress%20Tests/badge.svg)

* Contributors: [Ivan Moucha](https://github.com/IvanMoucha), [Andy Fragen](https://github.com/afragen), [Gary Jones](https://github.com/GaryJones), [Seth Carstens](https://github.com/sethcarstens), [Mikael Lindqvist](https://github.com/limikael), [contributors](https://github.com/afragen/github-updater/graphs/contributors)
* Tags: plugin, theme, update, updater, github, bitbucket, gitlab, remote install
* Requires at least: 5.2
* Requires PHP: 7.4
* Tested up to: trunk
* Stable tag: [master](https://github.com/IvanMoucha/github-updater/releases/latest)
* Donate link: <https://thefragens.com/github-updater-donate>
* License: GPLv2 or later
* License URI: <https://www.gnu.org/licenses/gpl-2.0.html>

A simple plugin to enable automatic updates to your GitHub, Bitbucket, GitLab, or Gitea hosted WordPress plugins, themes, and language packs. It also allows for the remote installation of plugins or themes.

[Install the latest version here.](https://github.com/afragen/github-updater/releases/latest)

## Description

This plugin was designed to simply update any GitHub hosted WordPress plugin or theme. Your plugin or theme **must** contain a header in the style.css header or in the plugin's header denoting the location on GitHub. The format is as follows.

    GitHub Plugin URI: IvanMoucha/github-updater
    GitHub Plugin URI: https://github.com/IvanMoucha/github-updater

or

    GitHub Theme URI: IvanMoucha/test-child
    GitHub Theme URI: https://github.com/IvanMoucha/test-child

...where the above URI leads to the __owner/repository__ of your theme or plugin. The URI may be in the format `https://github.com/<owner>/<repo>` or the short format `<owner>/<repo>`. You do not need both. Only one Plugin or Theme URI is required. You **should not** include any extensions like `.git`.

# claude-plugins

The Claude Code plugins of Azam Khan, as one marketplace called `azamkhanuk`.

## Install

Add the marketplace once:

```sh
claude plugin marketplace add azamkhanuk/claude-plugins
```

Then install a plugin by its name:

```sh
claude plugin install context-central@azamkhanuk
```

Or from inside a session:

```
/plugin marketplace add azamkhanuk/claude-plugins
/plugin install context-central@azamkhanuk
```

## The plugins

| Plugin | What it does |
|---|---|
| [context-central](https://github.com/azamkhanuk/context-central) | Gives all the context behind your work one central place: a map of plain Markdown notes about your repositories and the work in flight |

Each plugin lives in a repository of its own, with its own README, changelog and releases. This repository holds only the list.

## Update

A plugin carries a version, and an installed copy stays on its release until a newer one is published:

```sh
claude plugin marketplace update azamkhanuk
claude plugin update context-central@azamkhanuk
```

Auto-update is off by default for a marketplace you add yourself. To turn it on, open `/plugin`, go to Marketplaces, choose `azamkhanuk` and enable auto-update.

## Remove

Uninstall a plugin by its name. Removing the marketplace uninstalls every plugin you installed from it.

```sh
claude plugin uninstall context-central@azamkhanuk
claude plugin marketplace remove azamkhanuk
```

## Licence

[MIT](LICENSE).

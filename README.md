# Git Repository Manager

<p>
  <img src="icon.png" alt="Git Repository Manager" width="128"/>
</p>

A lightning-fast, frictionless, zero-dependency, zero-bloat, KISS repository manager that lists your personal and organizations GitHub repositories, allowing you to clone, open in browser, or create new ones if you want to. No more navigating through multiple pages to find the repo you need. Just click and go!

## 🚀 Installation

The VSIX package is available at [Open VSX Registry](https://open-vsx.org/extension/SPAjs/git-repo-manager) | [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=spajs.git-repo-manager).

1. Open any VS Code Family Editor (VS Code, Cursor, Windsurf, VSCodium).
2. Go to Extensions.
3. Search for `Git Repository Manager` and select this extension.
4. Click **Install**.

## ✨ Features

- **Blazing Fast & Lightweight:** Built strictly with Vanilla JavaScript and native APIs. Zero external dependencies, no compilation bloat.
- **Unified Repository View:** Access your Personal and Organization repositories in one clean, grouped sidebar panel.
- **Native Security:** Utilizes the editor's built-in GitHub authentication—no manual PAT setup required.
- **One-Click Actions:** Hover over any repository to Clone, Open in Browser, or Copy the URL.
- **Create on the Fly:** Add new public or private repositories directly to your personal account or organizations without leaving your editor.

## 🚀 Usage

You can trigger the extension from wherever you are working:
- **Sign In:** Click the `Git Repository Manager` icon in the Activity Bar and click the account icon at the top to securely authenticate.
- **Browse:** Expand your `Personal` folder or any listed `Organization` to view your repositories.
- **Hover Actions:** Hover over a repository to reveal quick actions: `Clone`, `Open in Browser`, and `Copy URL`. (These are also available via right-click context menu).
- **Create Repo:** Click the `+` icon next to an organization or personal folder to create a new repository under that specific account.
- **Manage Accounts:** Use the `Sign Out` or `Switch Account` icons in the panel header to seamlessly swap contexts.

## ⚙️ Extension Settings

This extension contributes the following settings to tailor it to your needs:

* `spajsGitRepoManager.defaultClickAction`: Sets the default action triggered when left-clicking a repository in the tree. 
  * Options: `none` (default), `browser` (Open in Browser), `clone` (Clone Repository), `copy` (Copy URL).

## ✨ Other Related VSIX Family Extensions

- Git SSH Config Manager -
  [Open VSX Registry](https://open-vsx.org/extension/SPAjs/git-ssh-config-manager)
  | [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=spajs.git-ssh-config-manager)

- Git Profile-Protocol Switcher -
  [Open VSX](https://open-vsx.org/extension/SPAjs/git-profile-protocol-switcher)
  | [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=spajs.git-profile-protocol-switcher)

- Git Snapshots -
  [Open VSX Registry](https://open-vsx.org/extension/SPAjs/git-snapshots)
  | [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=spajs.git-snapshots)

- Git Pull Agent -
  [Open VSX Registry](https://open-vsx.org/extension/SPAjs/git-pull-agent)
  | [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=spajs.git-pull-agent)

- Backup File -
  [Open VSX Registry](https://open-vsx.org/extension/SPAjs/backup-file)
  | [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=spajs.backup-file)

- Tagged File Snapshots -
  [Open VSX Registry](https://open-vsx.org/extension/SPAjs/tagged-file-snapshots)
  | [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=spajs.tagged-file-snapshots)

- Tagged Snapshots -
  [Open VSX Registry](https://open-vsx.org/extension/SPAjs/tagged-snapshots)
  | [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=SPAjs.tagged-snapshots)

- Backup Folder -
  [Open VSX Registry](https://open-vsx.org/extension/SPAjs/backup-folder)
  | [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=spajs.backup-folder)

## ☑️ Requirements

- VS Code (family) v1.82.0 or higher.
- Git installed on your system.

## ⚖️ License

MIT

## 🏠 Home

[GitHub](https://github.com/sucom/vsce-git-repo-manager)
# Awesome Git Tools

> The list is part of [Learn Git in a Day](https://faun.dev/sensei/academy/learn-git-in-a-day-fae561-02e121-dfadb8-e2e0a6-4bc/) course, but is also useful as a standalone resource for anyone looking to explore the ecosystem of Git tools.

A curated list of tools and utilities that enhance the Git experience, from GUI clients to command-line helpers, hooks, analytics, and more.

Fork and contribute if you have a favorite Git tool that isn't listed here! Only free, open-source, or freemium tools are included. Tools must be actively maintained and have a clear focus on enhancing Git workflows.

## GUI Clients

* [GitHub Desktop](https://desktop.github.com/): Free desktop Git client from GitHub.
* [SourceTree](https://www.sourcetreeapp.com/): Free Git GUI client for Windows and macOS.
* [Fork](https://git-fork.com): Fast and polished Git client for macOS and Windows.
* [TortoiseGit](https://tortoisegit.org/): Windows shell-integrated Git client.
* [RabbitVCS](http://rabbitvcs.org/): Graphical version control integration for Linux file managers.
* [gitg](https://wiki.gnome.org/Apps/Gitg/): GTK-based Git repository viewer and client.
* [git-cola](https://git-cola.github.io/): Cross-platform Git GUI built in Python.
* [SGit](https://github.com/sheimi/SGit): Git client for Android.
* [ungit](https://github.com/FredrikNoren/ungit): Web-based Git UI that runs locally.
* [GitUp](http://gitup.co): Lightweight Git client focused on visual history browsing.
* [Git Extensions](https://gitextensions.github.io/): Git GUI toolkit and shell integration for Windows.
* [Working Copy](https://workingcopyapp.com): Powerful Git client for iOS.
* [Gittyup](https://github.com/Murmele/Gittyup): Graphical Git client focused on understanding history.
* [GitAhead](https://gitahead.github.io/gitahead.com/): Open-source Git GUI for fast visual repo navigation.
* [Gitnuro](https://gitnuro.jetpackdroid.com/): Open-source cross-platform Git client built with Kotlin and Compose.
* [GitFiend](https://gitfiend.com/): Free cross-platform desktop Git client.
* [Vershd](https://vershd.io/): Free-for-personal-use Git GUI for desktop platforms.

## Terminal UI and CLI Enhancements

* [lazygit](https://github.com/jesseduffield/lazygit): Simple and popular terminal UI for Git.
* [gitui](https://github.com/extrawurst/gitui): Fast Rust-based terminal UI for Git.
* [Magit](https://magit.vc): Full-featured Git porcelain inside Emacs.
* [forgit](https://github.com/wfxr/forgit): `fzf`-powered interactive Git commands.
* [git-fuzzy](https://github.com/bigH/git-fuzzy): Fuzzy finder interface for common Git actions.
* [git-open](https://github.com/paulirish/git-open): Open the current repository page in the browser.
* [git-recent](https://github.com/paulirish/git-recent): Quickly jump back into recently used repositories.
* [git-standup](https://github.com/kamranahmedse/git-standup): Show daily commit activity for standups.
* [git-machete](https://github.com/VirtusLab/git-machete): Manage stacked branches and branch trees.
* [git-trim](https://github.com/foriequal0/git-trim): Clean up merged and stale local branches.
* [git-imerge](https://github.com/mhagger/git-imerge): Perform incremental merges to isolate conflicts.
* [difftastic](https://github.com/Wilfred/difftastic): Syntax-aware structural diff tool.
* [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy): Make Git diffs easier to read in the terminal.
* [git-interactive-rebase-tool](https://github.com/MitMaro/git-interactive-rebase-tool): Interactive editor for rebase todo lists.
* [ugit](https://github.com/Bhupesh-V/ugit): Undo and recover from Git commands more easily.
* [gitin](https://github.com/isacikgoz/gitin): Terminal browser for Git logs and status.
* [gh-dash](https://github.com/dlvhdr/gh-dash): Terminal dashboard for GitHub pull requests and issues.
* [tig](https://github.com/jonas/tig): Text-mode interface for browsing Git history.
* [delta](https://github.com/dandavison/delta): Better diff pager with syntax highlighting.
* [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt): Rich Bash prompt for Git repositories.
* [Starship](https://starship.rs/): Fast cross-shell prompt with Git context.

## Hooks and Quality Gates

* [pre-commit](https://pre-commit.com): Framework for managing multi-language Git hooks.
* [husky](https://github.com/typicode/husky): Easy Git hooks for JavaScript and Node.js projects.
* [Overcommit](https://github.com/brigade/overcommit): Extensible Git hook manager written in Ruby.
* [lefthook](https://github.com/evilmartians/lefthook): Fast hook manager for many project types.
* [Mookme](https://github.com/Escape-Technologies/mookme): Language-agnostic Git hook runner for monorepos.
* [quickhook](https://github.com/dirk/quickhook): Fast and opinionated Unix-style Git hook runner.
* [git-secrets](https://github.com/awslabs/git-secrets): Prevent secrets from being committed.

## Multi-Repository Management

* [myrepos](https://myrepos.branchable.com/): Manage many version control repositories from one tool.
* [mu-repo](https://fabioz.github.io/mu-repo/): Coordinate work across multiple Git repositories.
* [multi-gitter](https://github.com/lindell/multi-gitter): Apply automated changes across many repositories.
* [gitwalk](https://github.com/pazdera/gitwalk): Bulk process sets of Git repositories.
* [gr](http://mixu.net/gr/): Manage and update multiple Git repositories.
* [gitbatch](https://github.com/isacikgoz/gitbatch): Run Git operations across many repositories.
* [gickup](https://github.com/cooperspencer/gickup): Mirror and back up repositories between providers.
* [gitbackup](https://github.com/amitsaha/gitbackup): Back up GitHub, GitLab, and Bitbucket repositories.
* [soba](https://github.com/jonhadfield/soba): Scheduled repository backups with change detection.
* [ghq](https://github.com/motemen/ghq): Organize and clone remote repositories into a clean local structure.

## History Rewriting and Cleanup

* [BFG Repo-Cleaner](https://rtyley.github.io/bfg-repo-cleaner/): Fast cleanup tool for removing bad data from Git history.
* [git-filter-repo](https://github.com/newren/git-filter-repo): Modern replacement for `git filter-branch`.
* [git-absorb](https://github.com/tummychow/git-absorb): Automatically create fixup commits for the right parent commit.
* [git-follow](https://github.com/nickolasburr/git-follow): Track a file across renames and history changes.
* [git-cliff](https://github.com/orhun/git-cliff): Generate changelogs from Git history.

## Release and Commit Workflow

* [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog): Toolset for generating changelogs from conventional commits.
* [commitlint](https://github.com/conventional-changelog/commitlint): Lint commit messages against chosen conventions.
* [Commitizen](https://github.com/commitizen/cz-cli): Standardize commit messages with guided prompts.
* [release-it](https://github.com/webpro/release-it): Automate releases, tags, and changelog generation.
* [git-town](https://github.com/git-town/git-town): Automate common Git branching workflows.
* [gitflow](https://github.com/nvie/gitflow): Command-line helpers for the Git Flow model.

## Security and Signing

* [gitleaks](https://github.com/gitleaks/gitleaks): Scan repositories and history for secrets.
* [trufflehog](https://github.com/trufflesecurity/trufflehog): Find credentials and secrets in Git data.
* [git-crypt](https://github.com/AGWA/git-crypt): Transparent file encryption inside Git repositories.
* [git-secret](https://github.com/sobolevn/git-secret): Store encrypted secrets in Git.
* [gitsign](https://github.com/sigstore/gitsign): Keyless Git commit signing with Sigstore.
* [Gitrob](https://github.com/michenriksen/gitrob): Find sensitive files in public GitHub repositories.

## Analytics and Visualization

* [git-sizer](https://github.com/github/git-sizer): Analyze repository size and scalability risks.
* [git-quick-stats](https://github.com/arzzen/git-quick-stats): Fast repository statistics from the command line.
* [gitstats](https://github.com/hoxu/gitstats): Generate HTML reports from repository history.
* [Onefetch](https://github.com/o2sh/onefetch): Show repository summaries in the terminal.
* [Gource](https://gource.io/): Animated visualization of repository history.
* [gitgraph.js](https://gitgraphjs.com/): Render Git branch diagrams in the browser.
* [jc --git-log](https://kellyjonbrazil.github.io/jc/docs/parsers/git_log): Convert `git log` output into JSON.

## Diff and Merge Tools

* [Meld](https://meldmerge.org/): Visual diff and merge tool for Linux and Windows.
* [KDiff3](https://kdiff3.sourceforge.net/): Compare and merge files and directories.
* [P4Merge](https://www.perforce.com/products/helix-core-apps/merge-diff-tool-p4merge): Free visual merge and diff tool from Perforce.

## Large Files and Repository Extensions

* [Git LFS](https://git-lfs.github.com/): Store large files outside normal Git objects.
* [VFS for Git](https://github.com/microsoft/VFSForGit): Virtual file system that enables Git to work efficiently with very large repositories.
* [git-annex](https://git-annex.branchable.com/): Manage large files with Git-backed metadata.
* [gitfs](https://www.presslabs.com/gitfs/): Expose Git data through a FUSE filesystem.
* [Gitless](https://gitless.com/): Experimental version control system built on Git ideas.

## Repository Utilities

* [awesome-git-addons](https://github.com/stevemao/awesome-git-addons): Curated list of Git add-ons and extra commands.
* [git-extras](https://github.com/tj/git-extras): Collection of useful additional Git commands.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands): Another set of small Git helper commands.
* [gitignore](https://github.com/github/gitignore): Large collection of `.gitignore` templates.
* [etckeeper](https://etckeeper.branchable.com/): Keep `/etc` under version control with Git.
* [github/cli](https://github.com/github/cli): Official GitHub command-line interface.
* [hub](https://github.com/github/hub): Extend Git with GitHub-focused commands.
* [soft-serve](https://github.com/charmbracelet/soft-serve): Terminal-first self-hosted Git server.
* [Gitoxide](https://github.com/GitoxideLabs/gitoxide): Rust implementation of Git plumbing and tooling.
* [jj](https://github.com/jj-vcs/jj): Modern version control system with strong Git interoperability.
* [git-branchless](https://github.com/git-branchless/git-branchless): Workflow tools for branchless Git development.

## Self-Hosted Git Servers

* [Gitea](https://gitea.io/): Lightweight self-hosted Git service written in Go.
* [Forgejo](https://forgejo.org/): Community-driven fork of Gitea.
* [Gogs](https://gogs.io/): Simple self-hosted Git service.
* [Gitolite](https://gitolite.com/gitolite/): Access control layer for hosting Git repositories.
* [GitLab Community Edition](https://about.gitlab.com/install/): Self-hosted Git platform with CI/CD and project management.

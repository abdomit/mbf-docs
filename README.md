# MBF-DLS Documentation

This repository is the entry point for the **MBF-DLS documentation**.

The documentation itself is maintained in the **Wiki** associated with this repository.

➡️ **[Go to the MBF-DLS Wiki](https://github.com/abdomit/mbf-docs/wiki)**

## Repository contents

This repository contains the guidelines and metadata required to maintain the MBF-DLS documentation.

| File | Purpose |
|---|---|
| [`README.md`](README.md) | Entry point and overview of the documentation workflow |
| [`SYNTAX.md`](SYNTAX.md) | Markdown conventions and cross-platform compatibility rules |
| [`VERSIONS.md`](VERSIONS.md) | Mapping between MBF versions and wiki documentation commits |

## About the wiki repository

The documentation content itself is maintained in the project wiki, associated with this repository.

The wiki pages are designed to be compatible with both GitHub and GitLab wikis, despite differences in Markdown syntax and supported features. To ensure portability between the two platforms, wiki pages should use a relatively simple and widely supported subset of Markdown.

The wiki content does not contain any absolute references to the hosting platform. Consequently, it can be forked to another GitHub or GitLab instance and used without modification.

**This repository, however, contains absolute links** and may require modifications when forked to another location.

## How to clone the wiki repository

The wiki content is versioned in a dedicated Git repository and can be cloned using either HTTPS or SSH.

```bash
# Clone using HTTPS
git clone https://github.com/abdomit/mbf-docs.wiki.git

# Clone using SSH
git clone git@github.com:abdomit/mbf-docs.wiki.git
```

## Versioning

To access the documentation corresponding to a previous MBF version, retrieve the commit SHA recorded in `VERSIONS.md` and check out the corresponding commit in the wiki repository.

## Documentation guidelines

The [`SYNTAX.md`](SYNTAX.md) file describes the rules to follow when creating or modifying wiki pages.

These guidelines aim to ensure that the documentation remains compatible with both GitHub and GitLab wikis without requiring platform-specific modifications.

## Wiki maintenance notes

Keep the following points in mind when maintaining the wiki.

### Manually maintained tables of contents

Some wiki pages contain tables of contents that are **not generated automatically** and must be updated manually whenever pages are added, renamed, or removed.

The following files require particular attention:

- `_Sidebar.md`
- `home.md`
- `home-Help-Pages-for-Multi-Bunch-Feedback.md`
- `home-Help-Pages-for-Multi-Bunch-Feedback-(version-1.3).md`

### Visual editing

A visual editor can be helpful when creating or modifying complex page layouts.

In particular, the GitLab visual editor can be useful for editing complex tables, including tables with nested structures.

### Version tracking

Whenever a new MBF version is released, update `VERSIONS.md` with the commit SHA of the wiki documentation corresponding to that version.

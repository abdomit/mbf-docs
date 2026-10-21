# MBF-DLS Documentation Versions

This file records the association between **MBF versions** and the corresponding commits of the documentation wiki.

Each entry identifies the commit containing the documentation associated with a specific MBF version. This allows the documentation corresponding to a previous version of MBF to be retrieved.

## Version History

| MBF Version | Wiki Commit SHA |
|---|---|
| 1.4.2 | `<commit-sha-for-version-1.3>` |

## How to Access a Specific Version

To retrieve the documentation associated with a particular MBF version:

1. Find the corresponding commit SHA in the table above.
2. Clone the wiki repository, if you have not already done so.
3. Check out the corresponding commit.

For example, to access the documentation for MBF version 1.3:

```bash
git clone https://github.com/abdomit/mbf-docs.wiki.git
cd mbf-docs.wiki
git checkout <commit-sha-for-version-1.3>
```

This checks out the wiki content as it existed at the commit associated with MBF version 1.3.

**Note:** The commit SHA must refer to a commit in the wiki repository, not the main documentation repository.

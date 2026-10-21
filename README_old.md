# MBF-DLS Documentation

This repository is the entry point for the **MBF-DLS documentation**.

The documentation itself is maintained in the **Wiki** associated with this repository.

## Documentation

➡️ **[Go to the MBF-DLS Wiki](https://github.com/abdomit/mbf-docs/wiki)**

## About the wiki repository

The documentation content itself is maintained in the project wiki, associated with this repository.

The wiki pages are compatile with both Github and Gitlab environment, eventhough there are many differences in the syntaxe and available features. To achieve a good compatibility, the markdown elements used to write the pages has to remain relatively simple.

## How to clone the wiki repository

The wiki content is versioned in a Git repository, available to clone with:

```bash
# Clone with HTTPS
git clone https://github.com/abdomit/mbf-docs.wiki.git

# Clone with SSH
git clone git@github.com:abdomit/mbf-docs.wiki.git
```

The content of the wiki does not contain any absolute reference, which means that it can be forked in any Github or Gitlab instance and be used without any modification.

This is not the case with this repository, which contain absolute links.

## Version

The wiki documentation is following the MBF version.

In order to access the documentation of a former version, the SHA of the associated commit has to be know. It is indicated in the following file: VERSIONS.md

## Guides

The following guide can be used as an help about the rules that should be followed to modify this documentation. The purpose of these rules is to ensure that the wiki stay compatible with both Gitlab and Github wiki as it is (without any modification).

Link to the file SYNTAX.md

## Wiki maintenance notes

A couple things to keep in mind when updating the wiki:

- **Manually managed table of content**. A few files include a table of content which is **not auto-generated** and must always be edited by hand:

  - **`_Sidebar.md`**
  - **`home.md`**
  - **`home-Help-Pages-for-Multi-Bunch-Feedback.md`**
  - **`home-Help-Pages-for-Multi-Bunch-Feedback-(version-1.3).md`**

  They all need to be updated manually whenever wiki pages are added, renamed, or removed.

- **Editor**. Having a good visual editor can be very helpful to modify some pages. The Gitlab visual editor is specially helfull to design or modify complex tables, such as those including nested tables.

- **Version**. The file VERSIONS.md needs to be updates when a new version of the MBF is released, together with the SHA of the documentation associated.


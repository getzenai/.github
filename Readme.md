# Github Organization Configuration

With this special repository some aspects of the organization can be configured.

See the [Github docs for more information](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## Organization Public Page

The file `./profile/README.md` will be displayed as the [organizations public readme](https://github.com/Zen-Data).


## Issue templates

Issue templates for all repositories of the organization can be provided in the folder `.github/ISSUE_TEMPLATE/` as markdown files.

If a repository contains these folders, then these templates will be used instead.

The templates must contain the following frontmatter at the beginning

    ---
    name: A descriptive name
    about: Some helptext
    ---

This is then shown in the issue type picker when creating a new issue.
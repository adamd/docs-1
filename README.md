# Stoplight Docs

The time is nigh!

## Workflow

* All work should be done in a branch off of develop, and submitted via a PR upon completion.

## Templates

TODO

## Articles

TODO

## Assets

Assets (like images) should be placed in the assets/images folder.

JPEG, PNG, and GIF image formats are supported. Images can be included in markdown by using the relative path to the image.

For example:

```markdown
<!--- Inside of ./articles/organizations/overview.md --->

# Organization Overview

![my image](../../assets/images/my-image.jpg)
```

## Linking

Article A can link to Article B by using the file path to article B. This file path is relative to the root of the project.

For example:

```markdown
<!--- Inside of ./articles/organizations/overview.md --->

# Organization Overview

A link to [Projects Overview](../projects/overview.md).
```

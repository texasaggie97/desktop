# Issue and Pull Request Labels

This section outlines the labels currently used in the project, and adds context
about what each label represents.

## Shared labels

These labels are used for both issues and pull requests, and are assigned to
help understand the type of work involved.

|  | Label name | Description |
| ---- | ---------- | ----------- |
| [:mag_right:][docs] | `docs` | Issues and pull requests related to documentation work on the project |
| [:mag_right:][infrastructure] | `infrastructure` | Issues and pull requests related to scripts and tooling for GitHub Desktop |
| [:mag_right:][tech-debt] | `tech-debt` | Issues and pull requests related to addressing technical debt or improving the codebase |

## Issue-specific labels

This section is organized into sub-groups, as groups of labels relate to
specific work being done in the issue tracker.

### Triage

The triage process is how the maintainers process incoming issues and prioritize
the work required to address the feedback raised. These labels help us to track
the flow of an issue through this process

| Label name | :mag_right: | Description |
| ---------- | ----------- | ----------- |
| `bug` | [search](https://github.com/desktop/desktop/labels/bug) | Confirmed bugs or reports that are very likely to be bugs |
| `enhancement` | [search](https://github.com/desktop/desktop/labels/enhancement) |  |
| `investigation-needed` | [search](https://github.com/desktop/desktop/labels/reviewer-needs-to-reproduce)  | Likely bugs,
| `more-information-needed` | [search](https://github.com/desktop/desktop/labels/more-information-needed) | The submitter needs to provide more information about the issue |
| `priority-1` | [search](https://github.com/desktop/desktop/labels/priority-1) | Major bug affecting large population and inhibiting their work |
| `priority-2` | [search](https://github.com/desktop/desktop/labels/priority-2) | Bug that affects more than a few users in a meaningful way but doesn't prevent core functions |
| `priority-3` | [search](https://github.com/desktop/desktop/labels/priority-3) | Bugs that affect small number of users and/or relatively cosmetic in nature |

### External contributions

We use these labels to identify work that is ideal for external contributors
to get involved with.

| Label name | :mag_right: | Description |
| ---------- | ----------- | ----------- |
| `good-first-issue` | [search](https://github.com/desktop/desktop/labels/good-first-issue) | Issues marked as ideal for a brand new contributor to start with |
| `help-wanted` | [search](https://github.com/desktop/desktop/labels/help-wanted) | Issues marked as ideal for external contributors |

### Planning

We use these labels to track tasks outside the usual flow of addressing bugs or
implementing features:

| Label name | :mag_right: | Description |
| ---------- | ----------- | ----------- |
| `meta` | [search](https://github.com/desktop/desktop/labels/enhancement) | Issues used to co-ordinate tasks or discuss a feature before the required work is captured |
| `user-research` | [search](https://github.com/desktop/desktop/labels/user-research) | Issues that may benefit from user interviews, validations, and/or usability testing |
| `needs-design-input` | [search](https://github.com/desktop/desktop/labels/needs-design-input)  | Issues that require design input from the core team before the work can be started |

### Specialized areas

We use these labels to identify issues related to a specific area or the app,
or a specicif subset of users

| Label name | :mag_right: | Description |
| ---------- | ----------- | ----------- |
| `codemirror` | [search](https://github.com/desktop/desktop/labels/codemirror)  | Issues related to our use of [CodeMirror](https://codemirror.net/) that may require upstream fixes |
| `electron` | [search](https://github.com/desktop/desktop/labels/electron) | Issues related to our use of [Electron](https://electronjs.org) that may need updates to Electron or upstream fixes |
| `integrations` | [search](https://github.com/desktop/desktop/labels/integrations) | Issues related to editor and shell integrations that ship in Desktop |
| `themes` | [search](https://github.com/desktop/desktop/labels/themes) | Issues related the light or dark themes that ship in Desktop |

### Environments

Sometimes issues are isolated to a specific operating system. We use these
labels to help identify these issues, so maintainers with that setup - or
experience with that setup - can easily find them in the issue tracker.

| Label name | :mag_right: | Description |
| ---------- | ----------- | ----------- |
| `linux` | [search](https://github.com/desktop/desktop/labels/linux)  | Issues specific to Desktop usage on Linux |
| `macOS` | [search](https://github.com/desktop/desktop/labels/macOS)  | Issues specific to Desktop usage on macOS |
| `windows` | [search](https://github.com/desktop/desktop/labels/windows)  | Issues specific Desktop usage on Windows |


## Pull Request-specific labels

These labels should only be assigned to pull requests, and are intended to help
reviewers navigate the open contributions to identify how best to spend their
time:

| Label name | :mag_right: | Description |
| ---------- | ----------- | ----------- |
| `ready-for-review` | [search](https://github.com/desktop/desktop/labels/ready-for-review) | Pull Requests that are ready to be reviewed by the maintainers |


[docs]: https://github.com/desktop/desktop/labels/docs
[infrastructure]: https://github.com/desktop/desktop/labels/infrastructure
[tech-debt]: https://github.com/desktop/desktop/labels/tech-debt
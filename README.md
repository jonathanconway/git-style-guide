# Git Style Guide

A style-guide for naming things in Git. You may find it useful for enforcing a
convention on your project.

## Commit Messages

Commit messages must follow this format:

```
{type}({scope}) {subject}
<BLANK LINE>
{body}
<BLANK LINE>
{footer}
```

For example:

```
feat(keyword-search) limit search results for performance

Initial limit is 15, but may later be increased.
Also some refactoring was done.

JIRA-123
```

**Type**: Type of change being made. For example, adding a feature (`feat`) is
different from fixing a bug (`bug`) or modifying documentation (`docs`).

Examples of types you might use:
* **feat**: feature
* **fix**: bug fix
* **docs**: documentation
* **style**: formatting
* **ref**: refactoring code
* **test**: adding missing tests
* **chore**: maintenance or work-in-progress
* **content**: textual content

**Scope**: Scope of the change. This would usually refer to either a component
of the system being worked on (e.g. `login-flow`) or a feature of the system
(e.g. `keyword-search`).

**Subject**: Brief one-line summary of the change.

**Body**: A more elaborate explanation of the change and/or additional information
pertaining to the change.

**Footer**: This is where any relevant miscellaneous items, keywords, tags, ticket
numbers, etc. can be placed. Basically, information that doesn't need to be seen
up-front, but should be available for viewing by a human or searching/indexing
by a machine.

## Credits

Inspired by the [Deis Contributing Standards](http://docs.deis.io/en/latest/contributing/standards/#commit-style-guide).
Thanks [@freshtonic](https://github.com/freshtonic) for pointing me to the above.

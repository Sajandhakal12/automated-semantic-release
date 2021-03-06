## The commit header

The header is mandatory. It has a special format that includes a type, an optional scope, and a subject.

The header’s type is a mandatory field that tells what impact the commit contents have on the next version. It has to be one of the following types:

- feat: New feature
- fix: Bug fix
- docs: Change to the documentation
- style: Changes that do not affect the meaning of the code (e.g. white-space, formatting, missing semi-colons, etc.)
- refactor: Changes that neither fix a bug nor add a feature
- perf: Change that improves performance
- test: Add missing tests or corrections to existing ones
- chore: Changes to the build process or auxiliary tools and libraries, such as generating documentation

  The scope is a grouping property that specifies what subsystem the commit is related to, like an API, or the dashboard of an app, or user accounts, etc. If the commit modifies more than one subsystem, then we can use an asterisk (\*) instead.

The header subject should hold a short description of what has been done. There are a few rules when writing one:

Use the imperative, present tense (e.g. “change” instead of “changed” or “changes”).
Lowercase the first letter on the first word.
Leave out a period (.) at the end.
Avoid writing subjects longer than 80 charactersThe commit body.
Just like the header subject, use the imperative, present tense for the body. It should include the motivation for the change and contrast this with previous behavior.

## The commit footer

The footer should contain any information about breaking changes and is also the place to reference issues that this commit closes.

Breaking change information should start with BREAKING CHANGE: followed by a space or two new lines. The rest of the commit message goes here.

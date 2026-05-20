# bradyoolabs-screenshots

Public mirror of Playwright e2e screenshots for the [BradYooLabs](https://github.com/bradyoo12/BradYooLabs) (private) project.

Issue comments in the main repo embed images from here via
`https://raw.githubusercontent.com/bradyoo12/bradyoolabs-screenshots/master/<issue>/<filename>.png`
so reviewers can view them inline without needing repo-private auth.

## Layout

```
<issue_number>/
  01-<step>.png
  02-<step>.png
  ...
```

Screenshots are written by the `/b-start` (formerly `/b-todo`) skill in the main repo
when it detects frontend changes. See [BradYooLabs/.claude/commands/b-start.md](https://github.com/bradyoo12/BradYooLabs/blob/master/.claude/commands/b-start.md)
for the full flow and [BradYooLabs/e2e/](https://github.com/bradyoo12/BradYooLabs/tree/master/e2e)
for the Playwright spec sources.

Old shots may be pruned once an issue is closed and its branch is merged + deleted —
the linked ticket comments are the source of truth for what's still in use.

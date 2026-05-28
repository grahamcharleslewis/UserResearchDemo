# What we're gonna cover

## User Research Ask...

- Making commits and pushing them
- Making a pull request and dealing with checks
- Merging the approved pull request


## 1. Simple case - create file

- Create new branch
- Create `docs.md` and add content
- Add file
- Commit file
- Push branch
- Raise PR
- Approve and Merge


## 2. Broken check - update a file

- Create new branch
- Edit `.github/dependabot.yml` - change "gradle" to "mavern" but with a typo
- Add file
- Commit file
- Push branch
- Raise PR - this will cause the checks to fail - show check errors, fix error, update PR
- Approve and Merge
- Raise revert PR
- Approve and Merge


## 3. Dependabot PR's - approve and merge PR's

- View dependabot PR
- Review PR
- Approve and Merge

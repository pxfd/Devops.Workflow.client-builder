# Changelog

## [0.2.1 - 2022-11-15 ]
- Fix build status slack message

## [0.2.0 - 2022-11-14 ]
- Add branch name to git checkout directory to prevent code mix from various branches when cleanup script fails. E.g. runner hangs, workflow abort.
- Migrate from "set-output" to "GITHUB_OUTPUT"
- Last build commit per git branch
- All environment variables as upper case
- Move build data to `builds_data` subfolder
- Fix multiline changelog slack message
- Bump hashicorp/vault-action to v2.4.3

## [0.1.6 - 2022-11-07 ]
- Prevent workflow fails if there is slash char '/' in branch name

## [0.1.5 - 2022-11-07 ]
- Prevent workflow fails if there is a problem with git changelog diff

## [0.1.4 - 2022-11-01 ]
- Platform shared build number

## [0.1.3 - 2022-11-01 ]
- Add push tags for Addressables content repo

## [0.1.2 - 2022-10-13 ]
- Add dependabot
- Bump dependencies

## [0.1.1 - 2022-10-13 ]
- Add fallback to notifcation file

## [0.1.0 - 2022-10-12 ]
- Initial version
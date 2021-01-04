# Introduction

**All** dependencies use a pinned version in the `package.json` file.
So there are no ranges in use in the `package.json` for the defined dependencies.

NOTE: `not in diff` means that this is not part of the red/green parts of the diff on the GitHub interface.
It might still be present as an unchanged part of the diff, but that's not really relevant for us now.

## Dependencies comparison

| Dependencies                  | pinned to |                                    `yarn.lock` comparison                                    |
| ----------------------------- | :-------: | :------------------------------------------------------------------------------------------: |
| @renovate/pep440              |   0.4.1   |                                         not in diff                                          |
| @renovatebot/ruby-semver      |   0.2.1   |                                         not in diff                                          |
| @sindresorhus/is              |   4.0.0   |                                         not in diff                                          |
| @yarnpkg/core                 |   2.3.1   |                                         not in diff                                          |
| @yarnpkg/parsers              |   2.3.0   |                                         not in diff                                          |
| aws-sdk                       |  2.777.0  |                      upgraded to 2.778.0 as part of `aws-sdk@^2.637.0`                       |
| azure-devops-node-api         |  10.1.1   |                                         not in diff                                          |
| bunyan                        |  1.8.14   |                                         not in diff                                          |
| cacache                       |  15.0.5   |                                         not in diff                                          |
| chalk                         |   4.1.0   | "@jest/reporters@^26.6.1" has chalk "^4.0.0" as a dependency (in the green part of the diff) |
| changelog-filename-regex      |   2.0.1   |                                         not in diff                                          |
| clean-git-ref                 |   2.0.1   |                                         not in diff                                          |
| commander                     |   6.1.0   |                                         not in diff                                          |
| conventional-commits-detector |   1.0.3   |                                         not in diff                                          |
| deepmerge                     |   4.2.2   |                                         not in diff                                          |
| delay                         |   4.4.0   |                                         not in diff                                          |
| detect-indent                 |   6.0.0   |                                         not in diff                                          |
| email-addresses               |   3.1.0   |                                         not in diff                                          |
| fast-deep-equal               |   3.1.3   |                                         not in diff                                          |
| fast-safe-stringify           |   2.0.7   |                                         not in diff                                          |
| find-up                       |   5.0.0   |                                         not in diff                                          |
| fs-extra                      |   9.0.1   |                                         not in diff                                          |
| github-url-from-git           |   1.5.0   |                                         not in diff                                          |
| global-agent                  |  2.1.12   |                                         not in diff                                          |
| got                           |  11.8.0   |                                         not in diff                                          |
| handlebars                    |   4.7.6   |                                         not in diff                                          |
| handy-redis                   |   1.8.3   |                                         not in diff                                          |
| hasha                         |   5.2.2   |                                         not in diff                                          |
| ignore                        |   5.1.8   |                                         not in diff                                          |
| ini                           |   1.3.5   |                                         not in diff                                          |
| js-yaml                       |  3.14.0   |                                         not in diff                                          |
| jsdom                         |  16.4.0   |                                         not in diff                                          |
| json-dup-key-validator        |   1.0.2   |                                         not in diff                                          |
| json-stringify-pretty-compact |   2.0.0   |                                         not in diff                                          |
| json5                         |   2.1.3   |                                         not in diff                                          |
| later                         |   1.2.0   |                                         not in diff                                          |
| linkify-markdown              |   1.0.0   |                                         not in diff                                          |
| luxon                         |  1.25.0   |                                         not in diff                                          |
| markdown-it                   |  11.0.1   |                                         not in diff                                          |
| markdown-table                |   2.0.0   |                                         not in diff                                          |
| minimatch                     |   3.0.4   |                                         not in diff                                          |
| moment                        |  2.29.1   |                                         not in diff                                          |
| moment-timezone               |  0.5.31   |                                         not in diff                                          |
| node-emoji                    |  1.10.0   |                                         not in diff                                          |
| p-all                         |   3.0.0   |                                         not in diff                                          |
| p-map                         |   4.0.0   |                                         not in diff                                          |
| parse-diff                    |   0.7.1   |                                         not in diff                                          |
| parse-link-header             |   1.0.1   |                                         not in diff                                          |
| registry-auth-token           |   4.2.0   |                                         not in diff                                          |
| semver                        |   7.3.2   |  Was already present, also new as sub dep for "@typescript-eslint/typescript-estree@4.5.0"   |
| semver-stable                 |   3.0.0   |                                         not in diff                                          |
| semver-utils                  |   1.1.4   |                                         not in diff                                          |
| shlex                         |   2.0.2   |                                         not in diff                                          |
| shortid                       |  2.2.16   |                                         not in diff                                          |
| simple-git                    |  2.21.0   |                                         not in diff                                          |
| slugify                       |   1.4.5   |                                         not in diff                                          |
| toml                          |   3.0.0   |                                         not in diff                                          |
| traverse                      |   0.6.6   |                                         not in diff                                          |
| upath                         |   2.0.0   |                                         not in diff                                          |
| url-join                      |   4.0.1   |                                         not in diff                                          |
| validate-npm-package-name     |   3.0.0   |                                         not in diff                                          |
| www-authenticate              |   0.6.2   |                                         not in diff                                          |
| xmldoc                        |   1.1.2   |                                         not in diff                                          |

## Optional dependencies comparison

| Optional dependencies | pinned to | `yarn.lock` comparison |
| --------------------- | :-------: | :--------------------: |
| re2                   |  1.15.8   |      Not in diff       |

## devDependencies comparison

Done up to `@jest/globals`.
Needs further work.

| devDependencies                            | pinned to |                                                              `yarn.lock` comparison                                                              |
| ------------------------------------------ | :-------: | :----------------------------------------------------------------------------------------------------------------------------------------------: |
| @actions/core                              |   1.2.6   |                                                                   not in diff                                                                    |
| @babel/cli                                 |  7.12.1   |                                                                   not in diff                                                                    |
| @babel/core                                |  7.12.3   |                                                                   not in diff                                                                    |
| @babel/node                                |  7.12.1   |                                                                   not in diff                                                                    |
| @babel/plugin-proposal-class-properties    |  7.12.1   |                                                                   not in diff                                                                    |
| @babel/plugin-proposal-object-rest-spread  |  7.12.1   |                                                                   not in diff                                                                    |
| @babel/plugin-syntax-dynamic-import        |   7.8.3   |                                                                   not in diff                                                                    |
| @babel/preset-env                          |  7.12.1   |                                                                   not in diff                                                                    |
| @babel/preset-typescript                   |  7.12.1   |                                                                   not in diff                                                                    |
| @jest/globals                              |  26.6.0   |                    Gets upgraded to 26.6.1 as part of a range update, gets upgraded to 26.6.1 as dependency for jest-runtime                     |
| @jest/reporters                            |  26.6.0   |                         Gets upgraded to 26.6.1 as part of range update, gets installed as `"@jest/reporters@^26.6.1":`                          |
| @jest/test-result                          |  26.6.0   |                                                 Gets upgraded to 26.6.1 as part of range update,                                                 |
| @semantic-release/exec                     |   5.0.0   |                                                                   not in diff                                                                    |
| @types/bunyan                              |   1.8.6   |                                                                   not in diff                                                                    |
| @types/cacache                             |  12.0.1   |                                                                   not in diff                                                                    |
| @types/changelog-filename-regex            |   2.0.0   |                                                                   not in diff                                                                    |
| @types/clean-git-ref                       |   2.0.0   |                                                                   not in diff                                                                    |
| @types/conventional-commits-detector       |   1.0.0   |                                                                   not in diff                                                                    |
| @types/eslint                              |   7.2.4   |                                                                   not in diff                                                                    |
| @types/fs-extra                            |   9.0.2   |                                                                   not in diff                                                                    |
| @types/github-url-from-git                 |   1.5.0   |                                                                   not in diff                                                                    |
| @types/global-agent                        |   2.1.0   |                                                                   not in diff                                                                    |
| @types/ini                                 |  1.3.30   |                                                                   not in diff                                                                    |
| @types/jest                                |  26.0.15  |                                     not in diff, strangely enough, as other parts of Jest do get updated...                                      |
| @types/js-yaml                             |  3.12.5   |                                                                   not in diff                                                                    |
| @types/jsdom                               |  16.2.4   |                                                                   not in diff                                                                    |
| @types/json-dup-key-validator              |   1.0.0   |                                                                   not in diff                                                                    |
| @types/json5                               |  0.0.30   |                                                                   not in diff                                                                    |
| @types/later                               |   1.2.6   |                                                                   not in diff                                                                    |
| @types/linkify-markdown                    |   1.0.0   |                                                                   not in diff                                                                    |
| @types/luxon                               |  1.25.0   |                                                                   not in diff                                                                    |
| @types/markdown-it                         |  10.0.2   |                                                                   not in diff                                                                    |
| @types/markdown-table                      |   2.0.0   |                                                                   not in diff                                                                    |
| @types/moment-timezone                     |  0.5.13   |                                                                   not in diff                                                                    |
| @types/nock                                |  10.0.3   |                                                                   not in diff                                                                    |
| @types/node                                |  12.19.1  | Gets updated from 14.11.10 to 14.14.3 as part of wildcard update, also gets updated from 13.13.26 to 13.13.28 as part of `"@types/node@^13.7.0"` |
| @types/node-emoji                          |   1.8.1   |                                                                   not in diff                                                                    |
| @types/parse-link-header                   |   1.0.0   |                                                                   not in diff                                                                    |
| @types/registry-auth-token                 |   3.3.0   |                                                                   not in diff                                                                    |
| @types/semver                              |   7.3.4   |                                                                   not in diff                                                                    |
| @types/semver-stable                       |   3.0.0   |                                                                   not in diff                                                                    |
| @types/semver-utils                        |   1.1.0   |                                                                   not in diff                                                                    |
| @types/shelljs                             |   0.8.8   |                                                                   not in diff                                                                    |
| @types/traverse                            |  0.6.32   |                                                                   not in diff                                                                    |
| @types/xmldoc                              |   1.1.5   |                                                                   not in diff                                                                    |
| @typescript-eslint/eslint-plugin           |   4.4.1   |                                                                   not in diff                                                                    |
| @typescript-eslint/parser                  |   4.4.1   |                                   Gets entry for version 4.5.0 as part of `"@typescript-eslint/parser@^4.2.0"`                                   |
| aws-sdk-mock                               |   5.1.0   |                                                                   not in diff                                                                    |
| babel-jest                                 |  26.6.0   |           Gets entry for version 26.6.1 due to `babel-jest@^26.6.0` entry, also gets updated to 26.6.1 as part of normal range update            |
| babel-plugin-dynamic-import-node           |   2.3.3   |                                                                   not in diff                                                                    |
| conventional-changelog-conventionalcommits |   4.4.0   |                                                                   not in diff                                                                    |
| cross-env                                  |   7.0.2   |                                                                   not in diff                                                                    |
| eslint                                     |  7.11.0   |                                        eslint itself not in diff, but lots of subparts DO get updates...                                         |
| eslint-config-airbnb-typescript            |  11.0.0   |                                                                   not in diff                                                                    |
| eslint-config-prettier                     |  6.12.0   |                                                                   not in diff                                                                    |
| eslint-plugin-import                       |  2.22.1   |                                                                   not in diff                                                                    |
| eslint-plugin-jest                         |  24.1.0   |                                                                   not in diff                                                                    |
| eslint-plugin-promise                      |   4.2.1   |                                                                   not in diff                                                                    |
| glob                                       |   7.1.6   |                                       Version 7.1.2 gets installed as part of `"@jest/reporters@^26.6.1"`                                        |
| graphql                                    |  15.3.0   |                                                                   not in diff                                                                    |
| husky                                      |   4.3.0   |                                                                   not in diff                                                                    |
| jest                                       |  26.6.0   |                 522 matches for word `jest`, how do i filter to just `jest`? Lots of parts of jest get updated to 26.6.1 though!                 |
| jest-circus                                |  26.6.0   |                                                                   not in diff                                                                    |
| jest-extended                              |  0.11.5   |                                                                   not in diff                                                                    |
| jest-junit                                 |  12.0.0   |                                                                   not in diff                                                                    |
| jest-mock-extended                         |  1.0.10   |                                                                   not in diff                                                                    |
| jest-silent-reporter                       |   0.2.1   |                                                                   not in diff                                                                    |
| mockdate                                   |   3.0.2   |                                                                   not in diff                                                                    |
| nock                                       |  13.0.4   |                                                                   not in diff                                                                    |
| npm-run-all                                |   4.1.5   |                                                                   not in diff                                                                    |
| prettier                                   |   2.1.2   |                                                                   not in diff                                                                    |
| pretty-quick                               |   3.1.0   |                                                                   not in diff                                                                    |
| rimraf                                     |   3.0.2   |                                                                   not in diff                                                                    |
| semantic-release                           |  17.2.1   |                                                                   not in diff                                                                    |
| shelljs                                    |   0.8.4   |                                                                   not in diff                                                                    |
| strip-ansi                                 |   6.0.0   |                                                                   not in diff                                                                    |
| tmp-promise                                |   3.0.2   |                                                                   not in diff                                                                    |
| type-fest                                  |  0.18.0   |                                                                   not in diff                                                                    |
| typescript                                 |   4.0.3   |                                  Lots of updates for `@typescript-eslint` but not for typescript program itself                                  |

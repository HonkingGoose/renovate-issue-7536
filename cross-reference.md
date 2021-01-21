# Introduction

**All** dependencies use a pinned version in the `package.json` file.
So there are no ranges in use in the `package.json` for the defined dependencies.

If the `yarn.lock` table has no entry, it means that the dependency was not found in the red/green parts of the diff on the GitHub interface.
It might still be present as an unchanged part of the diff, but that's not really relevant for us now.

## Dependencies comparison

| Dependencies                  | pinned to |                                    `yarn.lock` comparison                                    |
| ----------------------------- | --------: | :------------------------------------------------------------------------------------------: |
| @renovate/pep440              |     0.4.1 |                                                                                              |
| @renovatebot/ruby-semver      |     0.2.1 |                                                                                              |
| @sindresorhus/is              |     4.0.0 |                                                                                              |
| @yarnpkg/core                 |     2.3.1 |                                                                                              |
| @yarnpkg/parsers              |     2.3.0 |                                                                                              |
| aws-sdk                       |   2.777.0 |                      upgraded to 2.778.0 as part of `aws-sdk@^2.637.0`                       |
| azure-devops-node-api         |    10.1.1 |                                                                                              |
| bunyan                        |    1.8.14 |                                                                                              |
| cacache                       |    15.0.5 |                                                                                              |
| chalk                         |     4.1.0 | "@jest/reporters@^26.6.1" has chalk "^4.0.0" as a dependency (in the green part of the diff) |
| changelog-filename-regex      |     2.0.1 |                                                                                              |
| clean-git-ref                 |     2.0.1 |                                                                                              |
| commander                     |     6.1.0 |                                                                                              |
| conventional-commits-detector |     1.0.3 |                                                                                              |
| deepmerge                     |     4.2.2 |                                                                                              |
| delay                         |     4.4.0 |                                                                                              |
| detect-indent                 |     6.0.0 |                                                                                              |
| email-addresses               |     3.1.0 |                                                                                              |
| fast-deep-equal               |     3.1.3 |                                                                                              |
| fast-safe-stringify           |     2.0.7 |                                                                                              |
| find-up                       |     5.0.0 |                                                                                              |
| fs-extra                      |     9.0.1 |                                                                                              |
| github-url-from-git           |     1.5.0 |                                                                                              |
| global-agent                  |    2.1.12 |                                                                                              |
| got                           |    11.8.0 |                                                                                              |
| handlebars                    |     4.7.6 |                                                                                              |
| handy-redis                   |     1.8.3 |                                                                                              |
| hasha                         |     5.2.2 |                                                                                              |
| ignore                        |     5.1.8 |                                                                                              |
| ini                           |     1.3.5 |                                                                                              |
| js-yaml                       |    3.14.0 |                                                                                              |
| jsdom                         |    16.4.0 |                                                                                              |
| json-dup-key-validator        |     1.0.2 |                                                                                              |
| json-stringify-pretty-compact |     2.0.0 |                                                                                              |
| json5                         |     2.1.3 |                                                                                              |
| later                         |     1.2.0 |                                                                                              |
| linkify-markdown              |     1.0.0 |                                                                                              |
| luxon                         |    1.25.0 |                                                                                              |
| markdown-it                   |    11.0.1 |                                                                                              |
| markdown-table                |     2.0.0 |                                                                                              |
| minimatch                     |     3.0.4 |                                                                                              |
| moment                        |    2.29.1 |                                                                                              |
| moment-timezone               |    0.5.31 |                                                                                              |
| node-emoji                    |    1.10.0 |                                                                                              |
| p-all                         |     3.0.0 |                                                                                              |
| p-map                         |     4.0.0 |                                                                                              |
| parse-diff                    |     0.7.1 |                                                                                              |
| parse-link-header             |     1.0.1 |                                                                                              |
| registry-auth-token           |     4.2.0 |                                                                                              |
| semver                        |     7.3.2 |  Was already present, also new as sub dep for "@typescript-eslint/typescript-estree@4.5.0"   |
| semver-stable                 |     3.0.0 |                                                                                              |
| semver-utils                  |     1.1.4 |                                                                                              |
| shlex                         |     2.0.2 |                                                                                              |
| shortid                       |    2.2.16 |                                                                                              |
| simple-git                    |    2.21.0 |                                                                                              |
| slugify                       |     1.4.5 |                                                                                              |
| toml                          |     3.0.0 |                                                                                              |
| traverse                      |     0.6.6 |                                                                                              |
| upath                         |     2.0.0 |                                                                                              |
| url-join                      |     4.0.1 |                                                                                              |
| validate-npm-package-name     |     3.0.0 |                                                                                              |
| www-authenticate              |     0.6.2 |                                                                                              |
| xmldoc                        |     1.1.2 |                                                                                              |

## Optional dependencies comparison

| Optional dependencies | pinned to | `yarn.lock` comparison |
| --------------------- | --------: | :--------------------: |
| re2                   |    1.15.8 |                        |

## devDependencies comparison

Done up to `@jest/globals`.
Needs further work.

| devDependencies                            | pinned to |                                                              `yarn.lock` comparison                                                              |
| ------------------------------------------ | --------: | :----------------------------------------------------------------------------------------------------------------------------------------------: |
| @actions/core                              |     1.2.6 |                                                                                                                                                  |
| @babel/cli                                 |    7.12.1 |                                                                                                                                                  |
| @babel/core                                |    7.12.3 |                                                                                                                                                  |
| @babel/node                                |    7.12.1 |                                                                                                                                                  |
| @babel/plugin-proposal-class-properties    |    7.12.1 |                                                                                                                                                  |
| @babel/plugin-proposal-object-rest-spread  |    7.12.1 |                                                                                                                                                  |
| @babel/plugin-syntax-dynamic-import        |     7.8.3 |                                                                                                                                                  |
| @babel/preset-env                          |    7.12.1 |                                                                                                                                                  |
| @babel/preset-typescript                   |    7.12.1 |                                                                                                                                                  |
| @jest/globals                              |    26.6.0 |                    Gets upgraded to 26.6.1 as part of a range update, gets upgraded to 26.6.1 as dependency for jest-runtime                     |
| @jest/reporters                            |    26.6.0 |                         Gets upgraded to 26.6.1 as part of range update, gets installed as `"@jest/reporters@^26.6.1":`                          |
| @jest/test-result                          |    26.6.0 |                                                 Gets upgraded to 26.6.1 as part of range update,                                                 |
| @semantic-release/exec                     |     5.0.0 |                                                                                                                                                  |
| @types/bunyan                              |     1.8.6 |                                                                                                                                                  |
| @types/cacache                             |    12.0.1 |                                                                                                                                                  |
| @types/changelog-filename-regex            |     2.0.0 |                                                                                                                                                  |
| @types/clean-git-ref                       |     2.0.0 |                                                                                                                                                  |
| @types/conventional-commits-detector       |     1.0.0 |                                                                                                                                                  |
| @types/eslint                              |     7.2.4 |                                                                                                                                                  |
| @types/fs-extra                            |     9.0.2 |                                                                                                                                                  |
| @types/github-url-from-git                 |     1.5.0 |                                                                                                                                                  |
| @types/global-agent                        |     2.1.0 |                                                                                                                                                  |
| @types/ini                                 |    1.3.30 |                                                                                                                                                  |
| @types/jest                                |   26.0.15 |                                      not in diff strangely enough, as other parts of Jest do get updated...                                      |
| @types/js-yaml                             |    3.12.5 |                                                                                                                                                  |
| @types/jsdom                               |    16.2.4 |                                                                                                                                                  |
| @types/json-dup-key-validator              |     1.0.0 |                                                                                                                                                  |
| @types/json5                               |    0.0.30 |                                                                                                                                                  |
| @types/later                               |     1.2.6 |                                                                                                                                                  |
| @types/linkify-markdown                    |     1.0.0 |                                                                                                                                                  |
| @types/luxon                               |    1.25.0 |                                                                                                                                                  |
| @types/markdown-it                         |    10.0.2 |                                                                                                                                                  |
| @types/markdown-table                      |     2.0.0 |                                                                                                                                                  |
| @types/moment-timezone                     |    0.5.13 |                                                                                                                                                  |
| @types/nock                                |    10.0.3 |                                                                                                                                                  |
| @types/node                                |   12.19.1 | Gets updated from 14.11.10 to 14.14.3 as part of wildcard update, also gets updated from 13.13.26 to 13.13.28 as part of `"@types/node@^13.7.0"` |
| @types/node-emoji                          |     1.8.1 |                                                                                                                                                  |
| @types/parse-link-header                   |     1.0.0 |                                                                                                                                                  |
| @types/registry-auth-token                 |     3.3.0 |                                                                                                                                                  |
| @types/semver                              |     7.3.4 |                                                                                                                                                  |
| @types/semver-stable                       |     3.0.0 |                                                                                                                                                  |
| @types/semver-utils                        |     1.1.0 |                                                                                                                                                  |
| @types/shelljs                             |     0.8.8 |                                                                                                                                                  |
| @types/traverse                            |    0.6.32 |                                                                                                                                                  |
| @types/xmldoc                              |     1.1.5 |                                                                                                                                                  |
| @typescript-eslint/eslint-plugin           |     4.4.1 |                                                                                                                                                  |
| @typescript-eslint/parser                  |     4.4.1 |                                   Gets entry for version 4.5.0 as part of `"@typescript-eslint/parser@^4.2.0"`                                   |
| aws-sdk-mock                               |     5.1.0 |                                                                                                                                                  |
| babel-jest                                 |    26.6.0 |           Gets entry for version 26.6.1 due to `babel-jest@^26.6.0` entry, also gets updated to 26.6.1 as part of normal range update            |
| babel-plugin-dynamic-import-node           |     2.3.3 |                                                                                                                                                  |
| conventional-changelog-conventionalcommits |     4.4.0 |                                                                                                                                                  |
| cross-env                                  |     7.0.2 |                                                                                                                                                  |
| eslint                                     |    7.11.0 |                                     eslint itself not found in diff, but lots of subparts DO get updates...                                      |
| eslint-config-airbnb-typescript            |    11.0.0 |                                                                                                                                                  |
| eslint-config-prettier                     |    6.12.0 |                                                                                                                                                  |
| eslint-plugin-import                       |    2.22.1 |                                                                                                                                                  |
| eslint-plugin-jest                         |    24.1.0 |                                                                                                                                                  |
| eslint-plugin-promise                      |     4.2.1 |                                                                                                                                                  |
| glob                                       |     7.1.6 |                                       Version 7.1.2 gets installed as part of `"@jest/reporters@^26.6.1"`                                        |
| graphql                                    |    15.3.0 |                                                                                                                                                  |
| husky                                      |     4.3.0 |                                                                                                                                                  |
| jest                                       |    26.6.0 |                 522 matches for word `jest`, how do i filter to just `jest`? Lots of parts of jest get updated to 26.6.1 though!                 |
| jest-circus                                |    26.6.0 |                                                                                                                                                  |
| jest-extended                              |    0.11.5 |                                                                                                                                                  |
| jest-junit                                 |    12.0.0 |                                                                                                                                                  |
| jest-mock-extended                         |    1.0.10 |                                                                                                                                                  |
| jest-silent-reporter                       |     0.2.1 |                                                                                                                                                  |
| mockdate                                   |     3.0.2 |                                                                                                                                                  |
| nock                                       |    13.0.4 |                                                                                                                                                  |
| npm-run-all                                |     4.1.5 |                                                                                                                                                  |
| prettier                                   |     2.1.2 |                                                                                                                                                  |
| pretty-quick                               |     3.1.0 |                                                                                                                                                  |
| rimraf                                     |     3.0.2 |                                                                                                                                                  |
| semantic-release                           |    17.2.1 |                                                                                                                                                  |
| shelljs                                    |     0.8.4 |                                                                                                                                                  |
| strip-ansi                                 |     6.0.0 |                                                                                                                                                  |
| tmp-promise                                |     3.0.2 |                                                                                                                                                  |
| type-fest                                  |    0.18.0 |                                                                                                                                                  |
| typescript                                 |     4.0.3 |                                  Lots of updates for `@typescript-eslint` but not for typescript program itself                                  |

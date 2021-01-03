This is basically me trying to make sense of the lockfile changes.
Still need to figure out what changes we care about.
After that I'll need to de-duplicate the list.

Based on https://github.com/renovatebot/renovate/pull/7551/files

---

From: `"@jest/console@^26.6.0":`
To: `"@jest/console@^26.6.0", "@jest/console@^26.6.1":`

Main dep: `@jest/console` 26.6.0 -> 26.6.1
Sub deps:

- `@jest/types` 26.6.0 -> 26.6.1
- `jest-message-util` 26.6.0 -> 26.6.1
- `jest-util` 26.6.0 -> 26.6.1

---

From: `"@jest/core@^26.6.0":`
To: `"@jest/core@^26.6.0", "@jest/core@^26.6.1":`

Main dep: `@jest/core` 26.6.0 -> 26.6.1
Sub deps:

- `@jest/console` 26.6.0 -> 26.6.1
- `@jest/reporters` 26.6.0 -> 26.6.1
- `@jest/test-result` 26.6.0 -> 26.6.1
- `@jest/transform` 26.6.0 -> 26.6.1
- `@jest/types` 26.6.0 -> 26.6.1
- `jest-changed-files` 26.6.0 -> 26.6.1
- `jest-config` 26.6.0 -> 26.6.1
- `jest-haste-map` 26.6.0 -> 26.6.1
- `jest-message-util` 26.6.0 -> 26.6.1
- `jest-resolve` 26.6.0 -> 26.6.1
- `jest-resolve-dependencies` 26.6.0 -> 26.6.1
- `jest-runner` 26.6.0 -> 26.6.1
- `jest-runtime` 26.6.0 -> 26.6.1
- `jest-snapshot` 26.6.0 -> 26.6.1
- `jest-util` 26.6.0 -> 26.6.1
- `jest-validate` 26.6.0 -> 26.6.1
- `jest-watcher` 26.6.0 -> 26.6.1

---

From: `"@jest/environment@^26.6.0":`
To: `"@jest/environment@^26.6.0", "@jest/environment@^26.6.1":`

Main dep: `@jest/environment` 26.6.0 -> 26.6.1
Sub deps:

- `@jest/fake-timers` 26.6.0 -> 26.6.1
- `@jest/types` 26.6.0 -> 26.6.1
- `jest-mock` 26.6.0 -> 26.6.1

---

From: `"@jest/fake-timers@^26.6.0":`
To: `"@jest/fake-timers@^26.6.1":`

Main dep: `@jest/fake-timers` 26.6.0 -> 26.6.1
Sub deps:

- `@jest/types` 26.6.0 -> 26.6.1
- `jest-message-util` 26.6.0 -> 26.6.1
- `jest-util` 26.6.0 -> 26.6.1

---

From: `"@jest/globals@26.6.0", "@jest/globals@^26.6.0":`
To: `"@jest/globals@26.6.0":`

This can probably be ignored, as it's just stripping a line.

---

From: `"@jest/reporters@26.6.0", "@jest/reporters@^26.6.0":`
To: `"@jest/globals@^26.6.1":`

Main dep: `@jest/globals` 26.6.0 -> 26.6.1
**New** sub deps added to lockfile:

- `@jest/environment` 26.6.1
- `@jest/types` 26.6.1
- `expect` 26.6.1

---

From: nothing
To: `"@jest/reporters@^26.6.1":`

**New** main dep: `@jest/reporters` 26.6.1
**New** Sub deps added to lockfile:

- `@bcoe/v8-coverage` 0.2.3
- `@jest/console` 26.6.1"
- `@jest/test-result` 26.6.1
- `@jest/transform` 26.6.1
- `@jest/types` 26.6.1
- `chalk` 4.0.0
- `collect-v8-coverage` 1.0.0
- `exit` 0.1.2
- `glob` 7.1.2
- `graceful-fs` 4.2.4
- `istanbul-lib-coverage` 3.0.0
- `istanbul-lib-instrument` 4.0.3
- `istanbul-lib-report` 3.0.0
- `istanbul-lib-source-maps` 4.0.0
- `istanbul-reports` 3.0.2
- `jest-haste-map` 26.6.1
- `jest-resolve` 26.6.1
- `jest-util` 26.6.1
- `jest-worker` 26.6.1
- `slash` 3.0.0
- `source-map` 0.6.0
- `string-length` 4.0.1
- `terminal-link` 2.0.0
- `v8-to-istanbul` 6.0.1

**New** optional sub dep added to lockfile:

- `node-notifier` 8.0.0

---

TODO: Filter trough rest of `yarn.lock` file.

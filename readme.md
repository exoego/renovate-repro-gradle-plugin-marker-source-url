# Gradle plugin update has no source link

## Current behavior

Renovate PRs that update the `com.diffplug.spotless` Gradle plugin have no link to the source repository.
The plugin marker POM (`com.diffplug.spotless:com.diffplug.spotless.gradle.plugin`) on the Gradle Plugin Portal has no `scm` or `url`.
The plugin artifact POM (`com.diffplug.spotless:spotless-plugin-gradle`) has `scm`, but Renovate does not read it.

Example: #1 (created by Mend Renovate)

## Expected behavior

Renovate PRs link to the [source repository](https://github.com/diffplug/spotless).

Example: #3 (created by Renovate CLI with the fix)

## Link to the Renovate PR

https://github.com/renovatebot/renovate/pull/48127

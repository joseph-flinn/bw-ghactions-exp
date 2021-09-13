# GitHub Actions Experimentation

These are a collection of GitHub Action Workflows for stripped down experimentation

### test-release
Tests a special release case with Electron apps so that we can create the GitHub release 
without allowing the auto-updating until we are done deploying all of the clients.

### build-artifact
Builds a simple artifact and uploads it to the workflow

### get-artifact
Gets a previously build artifact from a specified workflow (in this case, `build-artifact`)

  ## List any issues/stories/epics relevant to this pull request


  ## Checks to be performed by the reviewer of a pull request
  - [ ] Code changes are covered using UT and overall coverage (lines, functions and branches) stands at 100%
  - [ ] No unused and commented code in the PR
  - [ ] No commented or skipped or useless testcases in UT
  - [ ] All nodejs dependency modules are at latest level
  - [ ] CCT is passing with the PR changes
  - [ ] All new UT testcases have at least one expect or assert
  - [ ] Legitimately used 'ignore' statement
  - [ ] Code changes in PR are GDPR compliance
  - [ ] Changelog is updated - https://github.ibm.com/Cloud-Integration/loopback-connector-salesforce/blob/master/changelog.md. If yes, share link
  - [ ] Evidence are uploaded in the test-templates folder of this repo? If yes, share link
  - [ ] Does a Travis build pass?

  ## Critical checks (PRs not to be merged if these are not done)
  - [ ] Is manual test added to Box doc for iPaas and appconnect-psl for CPAK for changes done by this PR?
  - [ ] Regression tests are executed and results are updated in https://github.ibm.com/Cloud-Integration/loopback-connector-salesforce/tree/master/docs/test-templates
  - [ ] Is detect-secret run before doing GIT Push on the changes?

# Contributing to Acquia Lift GTM
Acquia Lift GTM feature requests, bugs, support requests, and milestones are tracked via the [GitHub issue queue](https://github.com/acquia/acquia-lift-gtm/issues).

Before submitting an issue or pull request, please read and take the time to understand this guide. Issues not adhering to these guidelines may be closed.

## Submitting issues

Please choose your issue type carefully. If you aren't sure, odds are you have a support request.
- **Feature request**: a request for a specific enhancement to be made to the Acquia Lift GTM. This is distinct from a bug in that it represents a _gap_ in functionality, rather than an instance of the plugin behaving badly. It is distinct from a support request in that it has a specific and atomic request for new functionality, rather than being a general request for help or guidance.
- **Bug report**: a clearly defined instance of Acquia Lift GTM not behaving as expected. It is distinct from a feature request in that it represents a mismatch between what _does_ and what _claims to do_. It is distinct from a support request in that it has _specific steps to reproduce the problem_ (ideally starting from a fresh installation of BLT and the plugin) and _justification_ as to why this is a problem rather than an underlying tool such as Composer or Drush.
- **Support request**: a request for help or guidance. Use this if you aren't sure how to do something or can't find a solution to a problem that may or may not be a bug. Before filing a support request, please review the FAQ for solutions to common problems and general troubleshooting techniques. If you have an Acquia subscription, consider filing a Support ticket instead of an issue on this Github repository in order to receive support subject to your SLA.

After you have chosen your issue type, make sure to fill out the issue template completely.

## Submitting pull requests

Please note the branch statuses documented in the README and [GitHub page](https://github.com/acquia/acquia-lift-gtm):
- Pull requests for enhancements will only be accepted for the active development branch.
- Pull requests for bug fixes will only be accepted for supported branches.
- When submitting a pull request for a bug fix or enhancement that may apply to multiple branches, please submit only a single PR to the latest development branch for review. A maintainer will backport the fix if appropriate.

Pull requests must also adhere to the following guidelines:
- PRs should be atomic and targeted at a single issue rather than broad-scope.
- PRs must contain clear testing steps and justification, as well as all other information required by the pull request template.
- PRs must pass automated testing and/or manual testing before they will be reviewed.

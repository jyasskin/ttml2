# TTML2 PROCESS GUIDELINES

The following guidelines apply to the various processes used in the development and maintenance of the TTML2 specification.

## Pull-Requests

A pull-request (PR) should be created for every non-trivial change to the specification; furthermore, each pull request should be associated with an issue.

When creating a remote branch that is intended to lead to a PR, that branch should be named ``issue-0000(-token)+`` where the issue number is zero filled into ``0000``. For example:

<pre>
issue-0158-use-of-60-seconds-in-clock-expression
issue-0156-create-customizations-section
</pre>

## Pull-Request Merging

The editor may merge a PR, with or without changes, at any time, and with or without notice. The editor may delegate the merging of a PR to the creator of the PR or to another party. If merging a PR has been delegated, then the editor and delegatee should coordinate mergers to avoid unintended conflicts.

PR merges occur only from a PR branch to the gh-pages (default) branch.

## Post Pull-Request Merge Issues

Since the pull-request merge process described above is based on a Commit-Then-Review (CTR) process, it is possible that issues may arise that require resolution post-merge, e.g.,

* technical problem with post-merge specification content
* editorial problem with post-merge specification content
* principled objection to merge

If such an issue should arise, then a new issue should be created, which should @mention the original issue in its title and/or descriptive text.

## Non-Pull-Request Commits

Only the editor or a delegated team member may perform a non-PR based commit. These should generally be limited to trivial changes or changes that do not affect specificiation content. If performed by a delegated team member, that member should coordinate with the editor to avoid unintended conflicts.


# Git In Practice Errata
## Unpublished
* Rewriting History and Disaster Recovery
  * Rebase commits on top of another branch: git rebase
    * Page 112: Figure 6.6 is identical to Figure 6.9:
      ![Figure 6.6](/images/06-GitXRebaseAfter.png)

      It should instead be:
      ![Figure 6.6](/images/06-GitXPullRebaseAfter.png)

* Advanced branching
  * Generating a version number based on previous tags: git describe
    * Page 96-97: `git push -tags` should instead be `git push --tags`

## Submissions
Submit errata here:
https://github.com/GitInPractice/Errata/issues/new

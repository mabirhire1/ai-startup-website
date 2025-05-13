# Tom and Jerry Workflow using Git and GitHub.

## 1. Git Installation
![Git Installation](img/screenshot01A-git-installation.png)

## 2. Git Verification
![Git Version](img/screenshot01-git-version.png)

## 3. Sign into GitHub and Click on New Repository 
![New Repository](img/screenshot02-new-repository.png)

## 4. Create a GitHub Repository 
![Create Repository](img/screenshot03-create-repository.png)

## 5. Copy HTTPS URL 
![Copy URL](img/screenshot04-copy-url.png)

## 6. Create folder and clone Repository 
![Copy URL](img/screenshot05-clone-repository.png)

## 7. Create New Branch for Tom
![Create Tom's Branch](img/screenshot06-create-update-nav-branch.png)

## 8. Check Branch
![Check Branch](img/screenshot07-update-navigation-branch.png)

## 9. Unstaged Changes 
![Unstaged Changes](img/screenshot08-unstaged-update-branch.png)

## 10. Staged Changes to Commit
![Staged Changes](img/screenshot09-staged-update-branch.png)

## 11. Commit and Push to Repository 
![Push to Repository](img/screenshot10-repository-update.png)

## 12. Contact Info Branch Creation and Push to te Repository
![Contact Branch](img/screenshot11-add-contact-information.png)

## 13. Updated GitHub Repository with Pull Request
![Pull Request](img/screenshot12-updated-github-repository.png)

## 14. On the Repository switch to update Information Branch
![Switch Branch](img/screenshot13-switch-to -update-nav-branch.png)

## 15. Create New Pull Request
![Pull Request](img/screenshot14-create-pr.png)

## 16. Check for Conflicts and Resolve if Any
![No Conflict](img/screenshot15-no-conflict.png)

## 17. Review and merge
![Review and Merge](img/screenshot16-pr-merged.png)

## 18. Switch to Contact Branch and Reconsile
![Reconsile Divergent Branch](img/screenshot17-reconsile-divergent-branch.png)

## 19. Create PR for Contact Branch
![Pull Request](img/screenshot18-create-pr-for-contact-branch.png)

## 20. Review Changes
![Review Changes](img/screenshot19-review-changes.png)

## 21. Merge PR
![Merge PR](img/screenshot20-pr-merged.png)

## 22. Switch to Main Branch and Pull current changes
![Update Main Branch](img/screenshot21-updated-branch.png)

## 22. Project Updated withh All Contributions
![Updated Project](img/screenshot22-all-branches-captured.png)

---

## ⚠️ Challenges Faced & Resolutions

| Challenge                         | Description                                                       | Resolution                                                        |
|----------------------------------|-------------------------------------------------------------------|-------------------------------------------------------------------|
| Committing to wrong branch       | Accidentally committed to `add-contact-info` instead of `main`    | Used `git checkout main`, ensured changes were in sync, then pushed correctly |

| Divergent branches error         | Got error while pulling: “need to specify how to reconcile”        | Used `git pull --rebase` to rebase instead of merge              |

| No upstream branch tracking      | Push error when branch wasn’t tracking remote                      | Used `git push --set-upstream origin add-contact-info`           |                    |

| Forgetting to switch branches    | Made edits in `main` by mistake                                    | Used `git stash`, switched to correct branch, then applied stash |


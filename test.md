gitGraph
     commit id: "Initial Commit"
     branch feature/base-css
     checkout feature/base-css
     commit id: "Update base.css"
     checkout main
     merge feature/base-css id: "Merge base-css to main"
     branch nonprod
     checkout nonprod
     merge main id: "Merge main to nonprod"
     branch prod
     checkout prod
     merge nonprod id: "Merge nonprod to prod"
     branch feature/bug-intro
     checkout feature/bug-intro
     commit id: "Introduce bug (text color)"
     checkout main
     merge feature/bug-intro id: "Merge bug to main"
     checkout nonprod
     merge main id: "Propagate bug to nonprod"
     branch hotfix/fix-bug
     checkout hotfix/fix-bug
     commit id: "Fix bug (background color)"
     checkout main
     merge hotfix/fix-bug id: "Merge hotfix to main"
     checkout nonprod
     merge main id: "Merge hotfix to nonprod"
     checkout prod
     merge nonprod id: "Merge nonprod to prod (hotfixed)"

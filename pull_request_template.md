# Requester Checklist
-   AB# all within the Pull Request Title
-   All items within the current sprint - if not it will need to be split or it will need to be discussed with the Dev and Testing Project Lead
-   Target branch is the current QA Environment
-   Conflicts resolved - when a conflict is complex get all parties involved in the conflict resolution
-   If the change contains a DB Change work item in DevOps is tagged with #DBUpdateRequired
- [ ]   I've confirmed all the items above have been checked and are ready for a merge

# Reviewer Checklist
-   Double Check the items in the Requester Checklist above
- [ ]   I've confirmed all the items above have been checked and are ready for a merge

## Optimisation / Standardisation
-   Repetition
-   Unoptimized code
-   Maintainable
-   Generic Code
-   Commons
-   Extending
-   Matching our Current Patterns
-   LINQ and Database call frequency and size
- [ ]   I've confirmed all the items above have been checked and are ready for a merge

If something is flagged here and it looks like it is an improvement this will normally impact the scope unless it is simple It should be made into another user story and implemented another time and discussed with the Dev Project Lead.

## Security
-   Auth Handers
-   Filters
-   Validation (Frontend and Backend)
-   Private controllers, Services and Functions
- [ ]   I've confirmed all the items above have been checked and are ready for a merge

## Scope
-   Change to another program or a common function that needs to be flagged for testers
-   Only changes for work items tagged.
-   Within this release
-   Public APIs impact, where we have to notify Vendors
-   Database changes
-   Schema Change and Migration Scripts
- [ ]   I've confirmed all the items above have been checked and are ready for a merge

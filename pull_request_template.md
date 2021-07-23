GitHub Pull Request Review Process
#Initial Checklist
-	Tagged with AB# correctly
-	AB# all within the Pull Request Title
-	All items within the current sprint
-	It will need to be split or it will need to be discussed with the Dev and Testing Project Lead
-	Target branch is the current QA Environment
-	Conflicts
-	When a conflict is complex get all parties involved in the conflict resolution
# Review Process
## Optimisation / Standardisation
-	Repetition
-	Unoptimized code
-	Maintainable
-	Generic Code
-	Commons
-	Extending
-	Matching our Current Patterns
-	LINQ and Database call frequency and size
If something is flagged here and it looks like it is an improvement this will normally impact the scope unless it is simple It should be made into another user story and implemented another time and discussed with the Dev Project Lead.
## Security
-	Auth Handers
-	Filters
-	Validation (Frontend and Backend)
-	Private controllers, Services and Functions
## Scope
-	Change to another program or a common function that needs to be flagged for testers
-	Only changes for work items tagged.
-	Within this release
-	Public APIs impact, where we have to notify Vendors
-	Database changes
-   Schema Change and Migration Scripts
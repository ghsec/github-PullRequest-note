# Github Pull Request Notes for me


## Git Pull Request

1. Fork repo
2. Clone repo
3. Open in VS Code
	```
	code -r .
	```
4. Check Git status
	```git status```
5. Check git logs
	```git log```
6. Swith to new branch
	```git checkout -b 'testing-demo'```
7. Get branch
	```git branch```
8. Make some changes on files
9. check git status again
	```git status```
10. Add changed file
	```git add <FILE_NAME>```
11. git commit
	```git commit -m 'Explain what is changed in file'```
12. Check git log again
	```git log```
13. Check status again
	```git status```
14. output remote git
	```git remote -v```
15. Push origin
	```git push origin```
16. check status
	```git status```
17. push origin by branch
	```git push origin <BRANCH_NAME>```
18. Refresh forked git page
19. Click on button `Compare & pull request`

### Original repo
20. add upsteram an original repo
	```git remote add upstream git@github.com:<USERNAME>/<Repo>.git```
21. Check remote origins and upstream
	```git remote -v```
22. grab all changes from original remote repo
	```git fetch upstream```
23. reset master - your git
	```git reset``
24. checkout master
	```git checkout master```
25. check again status
	```git status```
26. change master from upstream
	```git reset --hard upstream/master```
27. check again loig to verify changings
	```git log```
28. Update master
	```git push origin master```
29. Pull request		
	```git push upstream master```								 								 			

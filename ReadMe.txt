6/11/2018
If there is an error in authentication do these steps:
0. (not sure for this but you can try using this: SET GCM_VALIDATE=false)
1. Navigate to repository folder
2. Type: set GDM_TRACE=1
3. Do a git command: git push origin
4. The system will ask for username or password.
5. There will be errors but the command should proceed.
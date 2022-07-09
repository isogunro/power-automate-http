# How to break inheritance HTTP Request
**URI:** _api/Web/GetFolderByServerRelativeUrl('Employee Onboarding Folder/@{variables('FolderName')}')/ListItemAllFields/breakroleinheritance(copyRoleAssignments=false, clearSubscopes=false)
## Full Workflow Image
![uri](https://github.com/isogunro/power-automate-http/blob/main/images/FolderBrkInheritance.PNG)

## Break inheritance
![uri](https://github.com/isogunro/power-automate-http/blob/main/images/BreakInheritance.PNG)
**URI:** ***_api/Web/GetFolderByServerRelativeUrl('Employee Onboarding Folder/@{variables('FolderName')}')/ListItemAllFields/breakroleinheritance(copyRoleAssignments=false, clearSubscopes=false)***


## Get By Email -> Compose
![uri](https://github.com/isogunro/power-automate-http/blob/main/images/Compose-getPrincipalID_2.PNG)
***body('Get_By_Email')['d']['id']***

Roles you can specify for the above:
- Edit: 1073741830
- Contribute: 1073741827
- Read: 1073741826
- View Only: 1073741924

Steps to Integrate Azure Boards with Github
-------------------------------------------
1. In the Azure DevOps Project > Project Settings, click "Boards > GitHub Connections".
2. Authorize the Azure Boards to read content from your GitHub. Select the rquired Github Repo(s).
3. Authorize GitHub to install "Azure Boards" extension.
4. Go to Azure Boards and create a Task/Issue whatever. Note the ID.

Steps in Github
---------------
1. Create a Repo and some dummy content.
2. Commit the Content with the commit message "Fixed AB#<Id of the task mentioned above in step 4>.
3. Push the change.

Verify in Azure Boards
----------------------
1. Go to Azure Boards and track the Item mentioned in Step 4 above.
2. The item status should be updated as Fixed/Done/Closed depending on the Item type.

# Microsoft SharePoint REST API Postman Collections

This repository contains collections and environment variable files to import into Postman.

An overview of the SharePoint REST API can be found in the [official Microsoft documentation](https://docs.microsoft.com/en-us/sharepoint/dev/sp-add-ins/get-to-know-the-sharepoint-rest-service?tabs=csom).

## Setup

To setup the Postman collections follow these steps:

1. Download and install the latest version of [Postman](https://www.postman.com/).
2. Click **File | Import ...**.
3. Select **Import From Link**.
4. Paste the following two URLs and click **Import** after each:

`https://raw.githubusercontent.com/stuartmccoll/microsoft-sharepoint-rest-api-postman-collections/master/Microsoft%20SharePoint%20REST%20API.postman_collection.json`

`https://raw.githubusercontent.com/stuartmccoll/microsoft-sharepoint-rest-api-postman-collections/master/Microsoft%20SharePoint%20REST%20API.postman_environment.json`

You should now see the `Microsoft SharePoint REST API` collection on the left hand side **Collections** pane.

5. Click on the **No environment** dropdown in the top right hand corner.
6. Select **Microsoft SharePoint REST API environment**.
7. Click the **eye** icon to the right of this dropdown, then click **Edit**.
8. Enter in to the current (not initial) variables your SharePoint app registration details: `appReg_clientId` as your ClientID, `appReg_clientSecret` as your ClientSecret, `targetHost` as `<your_tenant_name>.sharepoint.com`, and `realm` as your tenant ID.
9. Select Update. Close the Manage Environments dialog. In the **Microsoft SharePoint REST API | Application** collection on left hand side. Click on the **Get Access Token** item. Then click on the Send button on the right hand side.

You're now ready to begin making requests to the Microsoft SharePoint REST API using other items in the collection.

## Contribute

You can contribute to this project by forking the repository and following the setup steps to import those files. When you've made your contributions in the Postman editor, use **File | Export** to overwrite the file in your forked branch. Then simply submit the forked branch as a pull request back to this repository.

## Thanks

Thanks to the [Microsoft Graph Postman Collections](https://github.com/microsoftgraph/microsoftgraph-postman-collections) repository for the inspiration.

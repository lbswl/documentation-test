The Impira platform enables you to configure the functionality that you want your users to have. It offers you predefined roles that group the functionality of the platform according to what a user can create, modify, and export. Therefore, by assigning roles to your users, you grant different permission levels to them in the Impira platform. 

You can also configure which assets your users can see and how they can see them by using _Usage Windows_. Refer to the article, [How-To Model Usage Rights](https://support.impira.com/hc/en-us/articles/360033287731-How-To-Model-Usage-Rights) for more details on this topic.

**Note:** Only users with the **Owner** and **Administrator** roles can configure user access. If you are assigned to any of these roles, you can provide access to other users and configure Usage Windows. 

The following sections explain the predefined roles that Impira offers, permission levels, and the tasks that you can perform when configuring user access:


*   [Predefined Roles](#predefined-roles)
*   [Permission Levels](#permission-levels)
*   [Permission Access](#permission-access)


# Predefined Roles

You can assign one of the below predefined roles to a user depending on the capabilities that you want them to have. The predefined roles that Impira offers include:


*   **Owner:** Creates other owners and deletes admins.
*   **Admin:** Provides access to other users and configures account-wide settings.
*   **Collaborator:** Views, uploads, downloads, and deletes data.
*   **User:** Views, uploads, and downloads data but has no deletion or archival permissions.
*   **Guest:** Has read-only access with very limited exporting capabilities. This role can only export contact sheets.
*   **Export Only:** Views all data and prepares it for downstream use.
*   **Upload Only:** Uploads and sees only the uploaded data to the platform.

The spectrum of permissions spans from the **Admin** role which can configure account-wide settings that govern all the functionality Impira offers to roles such as **Guest**, **Export Only**, and **Download** **Only** which have limited capabilities to only view and download assets. 


# Permission Levels

The following table lists the functionality that each role can access in the Impira platform.


<table>
  <tr>
   <td><strong>Capability</strong>
   </td>
   <td><strong>Owner</strong>
   </td>
   <td><strong>Admin</strong>
   </td>
   <td><strong>Collaborator</strong>
   </td>
   <td><strong>User</strong>
   </td>
   <td><strong>Guest</strong>
   </td>
   <td><strong>Export Only</strong>
   </td>
   <td><strong>Upload Only</strong>
   </td>
  </tr>
  <tr>
   <td>Delete Admins
   </td>
   <td>✓
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Access Admin Panel
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Create Other Admins
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Create Usage Windows
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Apply/Edit Usage Windows
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Upload Assets
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>✓
   </td>
  </tr>
  <tr>
   <td>See Uploads
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>✓
   </td>
  </tr>
  <tr>
   <td>Add/Set Metadata
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Delete Assets
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Archive Assets
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Export Contact Sheets
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Download access
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
  </tr>
  <tr>
   <td>See Private/Public Collections
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Create Collections
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
  </tr>
  <tr>
   <td>Add to Collections
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
   <td>
   </td>
   <td>✓
   </td>
   <td>✓
   </td>
  </tr>
</table>


A user with an **Upload Only** role can only download the assets that they uploaded to the platform.

## Permission Access

New text. This is another sentence.
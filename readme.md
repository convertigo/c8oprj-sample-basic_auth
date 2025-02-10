


# BasicAuth

Demo project for dynamic Basic Authentication


For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Sequences](#sequences)
    - [Get_Auth_Basic](#get_auth_basic)
    - [Set_Auth_Basic](#set_auth_basic)


## Installation

1. In your Convertigo Studio click on ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/icons/studio/project_import.gif?raw=true "Import a project in treeview") to import a project in the treeview
2. In the import wizard

   ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/tomcat/webapps/convertigo/templates/ftl/project_import_wzd.png?raw=true "Import Project")
   
   paste the text below into the `Project remote URL` field:
   <table>
     <tr><td>Usage</td><td>Click the copy button at the end of the line</td></tr>
     <tr><td>To contribute</td><td>

     ```
     BasicAuth=C:/Convertigo/Studio 8.3.2/workspace/BasicAuth/.git:branch=master
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     BasicAuth=C:/Convertigo/Studio 8.3.2/workspace/BasicAuth//archive/master.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __BasicAuth__ project


## Sequences

### Get_Auth_Basic

Get dynamic Basic user credentials

### Set_Auth_Basic

Set dynamic Basic user credentials

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>pwd</td><td>Basic Password</td>
</tr>
<tr>
<td>user</td><td>Basic User</td>
</tr>
</table>




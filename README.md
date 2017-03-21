# Umrako - mandatory assignment
#### Development Environments - BAAA, Web Development semester 2
*Created: 21.03.2017*

## Installation
* Make sure that you have MS SQL server installed - [Download](https://www.microsoft.com/en-us/download/details.aspx?id=29062) (select ENU\x64\SQLEXPR_x64_ENU.exe, ENU\x64\SqlLocalDB.MSI and ENU\x64\SQLManagementStudio_x64_ENU.exe)
* Restore the `database` file in SQL Server Management Studio
* Open `Umrako.sln`
* Web.config - set the connection string to use your own server `Server=*your-pc*\SQLEXPRESS;`
* Web.config - set you your own SMTP `<network host="smtp.gmail.com" port="587" enableSsl="true" defaultCredentials="false" userName="test@gmail.com" password="test"/>`
* Run the solution
* In case of any problems - delete `.vs/config/` folder and change the port on which the project is running (in Visual Studio - Project->Umrako properties, Web tab

## Contributors
[Jakub Gilis](https://github.com/jacobg213) and [Daniel Szerszeń](https://github.com/roszpun)

Special thanks to [Mateusz Kopec](https://github.com/makop90)

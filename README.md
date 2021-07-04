# SitefinityWebApp for DotNet Framework

boilerplate Sitefinity CMS app

Do fail a couple of times before one is able to create a boilerplate sitefinity app. 
Adding Sitefinity nuget packages can take an ave of 12 minutes and still will build fine 
after failing to add 1 or 2 dependencies because of timeout issues. 

The official website explains how to set this up. 

https://www.progress.com/documentation/sitefinity-cms/install-sitefinity#configure-sitefinity-nuget-repository

If you encounter an error during setup you could also delete the package folder 
contents, clear Nuget packages and the re-add the Sitefinity Nuget packages if 
one is to encounter a version mismatch error between asp.net and sitefinity dlls.

One needs to have SSMS and SQL Server 2019 Instance/EXPRESS installed. 
Also encountered DB related permission errors here as well. Mixed mode 
authentication allows the use of either Windows or SQL Server credentials. 

If one encounters an error on SSMS while trying to provide permissions to sysadmin 
role in DB to a Login user account after logging with SQL Server credentials, then 
disconnect/log out and re-login/re-connect with Windows credentials and provide
persmissions

On the localhost Sitefinity site one can test with both Windows & Sql server 
authentication, only if mixed mode authentication is enabled on SQL Server 2019 
Instance/Express. 



There is a one month trial version license for developers you will need and the link below 
will explain how to get it from their official site -

https://knowledgebase.progress.com/articles/Article/Download-Sitefinity-license 



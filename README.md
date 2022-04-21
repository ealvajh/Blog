# Blog
This is a space where I have some notes and links.

- Add personal token: 
      https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token
- Markdown Guide: 
     https://www.markdownguide.org/cheat-sheet/

- Git: https://gitexplorer.com/

git remote add [name] [url]
git branch -M main
git push -u origin main

Pasos para crear una app .Net Core Web Api - dbfirst:

1. Crear app
2. agregar paquetes mediante nuget
	
	Install-Package Microsoft.EntityFrameworkCore.Tools
	Install-Package Microsoft.EntityFrameworkCore.SqlServer

3. Generar models

Scaffold-DbContext "Server=(localdb)\MSSQLLocalDB;Database=OnlineStore;Trusted_Connection=True;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models


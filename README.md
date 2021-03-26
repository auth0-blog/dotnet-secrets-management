This repository contains a basic ASP.NET MVC application secured with [Auth0](https://auth0.com/).

It is used as the starting-point application for the article: [Secrets Management in .NET Applications](https://auth0.com/blog/secret-management-in-dotnet-applications/)

---
### Technology

This project uses the following technologies:

- [.NET Core SDK 3.1](https://dotnet.microsoft.com/download/dotnet-core/3.1)
- [Auth0](https://auth0.com/)

### Running the Application

To run this project, follow these steps:

1. Clone this repository (`git clone https://github.com/auth0-blog/dotnet-secrets-management`)

2. [Register the ASP.NET MVC application with Auth0](https://auth0.com/blog/secret-management-in-dotnet-applications/#The.Sample.Application)

3. Move to the root folder of the project in your machine and edit the `appsettings.json` configuration file by filling the Auth0 required parameters

4. In the same folder, run the following command in a terminal window:

   ```shell
   dotnet run
   ```

7. Now, point your browser to [https://localhost:5001](https://localhost:5001/). You should be able to authenticate and access the application



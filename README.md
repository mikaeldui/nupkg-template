# NuGet Package Template Repository
A template repository for NuGet packages.

The repository name will be used when creating the solution, and it's less hassle to change the repo name afterwards than to create everything manually.

`NUGET_ORG_API_KEY` needs to be added as a secret for the `nuget.org` environment.

Contains:

    root/
    ├─ .github/
    │  ├─ workflows/
    │  │  ├─ codeql-analysis.yml
    │  │  ├─ dotnet.yml
    │  ├─ dependabot.yml
    ├─ RepositoryName/
    │  ├─ RepositoryName.csproj
    │  ├─ Class1.cs
    ├─ RepositoryName.Tests/
    │  ├─ RepositoryName.Tests.csproj
    │  ├─ TestClass1.cs
    ├─ .gitignore
    ├─ LICENSE
    ├─ README.md
    ├─ SECURITY.md
    ├─ RepositoryName.sln
    
## Thanks

Thanks to [Liam Gulliver](https://github.com/lgulliver) for his great [tutorial](https://lgulliver.github.io/dynamically-generate-projects-with-github-templates-and-actions/).

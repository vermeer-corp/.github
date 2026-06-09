# .github

This repo contains the Vermeer profile markdown and GitHub Actions workflow templates.

## Workflow Templates

To use these templates, see [Using starter workflows](https://docs.github.com/en/actions/using-workflows/using-starter-workflows#using-starter-workflows) in the GitHub Actions documentation.

---

### .NET Core/5/6 On-Premises CI/CD

<img src="./workflow-templates/net.svg" title=".NET Core/5/6 On-Premises CI/CD" alt=".NET Core/5/6 On-Premises CI/CD" width="64"/>

Per-environment template for building and deploying .NET Core/5/6 applications on-premises using GitHub Actions.

**Use of this template requires the use of the _Deploy On-Premises IIS_ template.**

---

### .NET Framework 4.x On-Premises CI/CD

<img src="./workflow-templates/net.svg" title=".NET Framework 4.x On-Premises CI/CD" alt=".NET Framework 4.x On-Premises CI/CD" width="64"/>

Per-environment template for building and deploying .NET Framework 4.x applications on-premises using GitHub Actions.

**Use of this template requires the use of the _Deploy On-Premises IIS_ template.**

---

### Vue.js On-Premises CI/CD

<img src="./workflow-templates/vue.svg" title="Vue.js On-Premises CI/CD" alt="Vue.js On-Premises CI/CD" width="64"/>

Per-environment template for building and deploying Vue.js applications on-premises using GitHub Actions.

**Use of this template requires the use of the _Deploy On-Premises IIS_ template.**

---

### Deploy On-Premises IIS

<img src="./workflow-templates/web-server.svg" title="Deploy On-Premises IIS" alt="VDeploy On-Premises IIS" width="64"/>

Deploy the specified artifact to an on-premises IIS and replace secrets in specified config files.

---

### GitLeaks Secret Scan

<img src="./workflow-templates/gitleaks.svg" title="GitLeaks Secret Scan" alt="GitLeaks Secret Scan" width="64"/>

Detect passwords, API keys, private keys, and other secrets that have been committed to the codebase.

---

### SonarQube SAST Scan

<img src="./workflow-templates/SonarQube.svg" title="SonarQube SAST Scan" alt="SonarQube SAST Scan" width="64"/>

Statically analyze code to check for code smells, security issues, and other potential problems. There are different versions of this template depending on the project's programming language.

---

### .NET Core/Standard/5/6 NuGet CI/CD to GitHub Packages

<img src="./workflow-templates/nuget.svg" title=".NET Core/Standard/5/6 NuGet CI/CD to GitHub Packages" alt=".NET Core/Standard/5/6 NuGet CI/CD to GitHub Packages" width="64"/>

CI/CD template for building, testing, and publishing .NET Core/Standard/5/6 NuGet packages to GitHub Packages.

**Note: This workflow requires a `RepositoryUrl` attribute in the .csproj file to publish to GitHub Packages.**

```xml
    <PropertyGroup>
        <TargetFrameworks>netcoreapp3.1;net50;net60</TargetFrameworks>
        <Version>...</Version>
        <PackageId>...</PackageId>
        <PackageDescription>...</PackageDescription>
        <RepositoryUrl>https://github.com/vermeer-corp/repo-url.git</RepositoryUrl>
    </PropertyGroup>
```

---

### .NET Framework NuGet CI/CD to GitHub Packages

<img src="./workflow-templates/nuget.svg" title=".NET Framework NuGet CI/CD to GitHub Packages" alt=".NET Framework NuGet CI/CD to GitHub Packages" width="64"/>

CI/CD template for building, testing, and publishing .NET Framework NuGet packages to GitHub Packages.

**Note: This workflow requires a `projectUrl` and `repository` attribute in the .nuspec file to publish to GitHub Packages.**

```xml
<?xml version="1.0"?>
<package >
  <metadata>
    ...
    <projectUrl>https://github.com/vermeer-corp/repo-url</projectUrl>
    <repository type="git" url="https://github.com/vermeer-corp/repo-url.git"/>
    ...
  </metadata>
  ...
</package>
```

---

### Mendix Actions

<img src="./workflow-templates/mendix.svg" title="Mendix Actions" alt="Mendix Actions" width="64"/>

CI/CD template for building, deploying, and managing the versions of Mendix Applicaiton Projects.

**Use of this template requires the use of the _Build and Deploy on Mendix Cloud_ and the _Update Version Number of Mendix App_ template.**

---

### Vermeer Industrial Systems Actions

<img src="./workflow-templates/vermeer.svg" title="Vermeer" alt="Vermeer" width="64"/>

#### Build Simulink Controller Models

Build one or more Simulink controller models defined in a repository.

#### Build Simulink Library

Create a distributable version of a Simulink library that can be imported as a submodule for Simulink projects.

#### Delete Dist Branches

Delete all dist branches prefixed with an inputted name.

#### Deploy to TechDocs

Set up and deploy a VME repository's MkDocs documentation to TLDR's TechDocs component.

#### Export Simulink Project

Export a Simulink project to a format for distribution to other Simulink projects.

#### Reload Model Parameters

Reload parameters in one or more Simulink models defined in a repository.

#### Run Simulink Project Tests

Run `Vermeer_Test_Tools` unit tests defined in a Simulink project.

#### Update Project Models

Update Simulink models in a given MATLAB project.

---

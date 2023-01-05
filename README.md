# DevOps-home-assignment-junior

## Before starting the exercise:
1. Make sure you have Visual Studio or Visual Studio Tools
(mandatory: msbuild.exe, vc++)
2. Create a free account in Microsoft Azure DevOps
3. Create a .NET CLI "Hello world" project
4. Create a new repo in Azure Devops (free account)
5. Upload the project files to branch 'main'

## The exercise:
Fork this repo first.  if you don’t know what fork is google it.

### Phase A: Create a new yaml pipeline:
Note: Pipeline must run on a clean machine or Microsoft Container
1. Build the solution
2. Upload the product to Artifactory or Azure DevOps Artifact, with property of your choice (You can run artifactory server on a container)
3. Increment version number (you decide how)
4. Print version number to the console (from AssemblyInfo.cs)
### Phase B: Create another pipeline Or use conditions:
1. Create a new branch, from 'main'
2. Run SonarQube scan and publish to server
3. Add library project and build the solution
4. Create NuGet file from the DLL
5. Upload the product to Artifactory (NuGet repo type), with another
property of your choice (you decide)
6. Print version number to the console (from AssemblyInfo.cs)
7. Create a tag with the name test_[version_number]
8. Push the changes (version number + tag)
9. Send email to an address of your choice
Good Luck!


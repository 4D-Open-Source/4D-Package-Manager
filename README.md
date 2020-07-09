# 4D-Package-Manager
The start of a package manager component to let 4D developers find open sourced code to be used in their own projects.

### Requirements Wish List
- Able to search methods that developers have published on github. At a minium, can search methods that have been published on 4D Open Source github.
  __NOTE__ [dbeaubien/4D-Github-API-Component](https://github.com/dbeaubien/4D-Github-API-Component) has sample code that shows how to fetch a file off a github repository.
- Be able to search by type (method, component, example?), contents of title, github tags, etc. Implies that we will need to collect that information. Could be done using GitHub APIs.
- Developers can select methods they want and have them added to their structures. The component will need to keep track (in the structure's Resources folder) which methods were downloaded and which version.
- The package manager should be able to detect when there is a newer verion on github and let the developer update their code
- Able to do the same for components.
- Able to do the same for example code.
- Able to submit bug fixes.
- Able to add new resources.

### Goals
- Easy to use
- Easy to see if there are updates that need to be downloaded
- Easy for people to contribute fixes.

### Problems to Overcome
- How to publish methods and manage any dependencies
- How to publish components and manage any dependencies
- How to let developers submit bug fixes
- How to let developers include their own resources

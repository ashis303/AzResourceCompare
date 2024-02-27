# AzResourceCompare

# Introduction
This project is designed for comparing resources and their configurations. Resources can be hosted locally or in remote subscriptions. It provides scenarios for comparing configurations after migrating resources from one tenant to another or from one environment to another.
 
 
## Table of Contents
- [Permissions Pre-req](#permissions)
- [Extending the Tool](#extending-the-tool)
 
 
<a name="permissions"></a> Permissions
To contribute to this project, you'll need the following permissions:
- A service principal account per subscription to access its resources.
- Subscription reader permission for the service principal is sufficient to execute the tool.
 
 
<a name="extending-the-tool"></a> Extending the Tool
- Understand Existing Structure: Familiarize yourself with the existing code structure and how the current methods are implemented.
- Identify New Resource Type: Determine the type of resource you want to add support for. This could be a specific Azure service or any other type of Az resource.
- The tool can be easily extended by adding respective methods in the code. As of now, the code includes methods for WebApp and Azure Storage integration. Below are the steps to extend the tool by adding new methods:
- Implement New Method: Create a new method in the codebase to handle the comparison of the new resource type. Ensure that the method follows the conventions and standards used in the existing code.
 
 
 
## Contribution: 
If you would like to contribute and once you're confident that your changes are ready, submit a pull request to the repository. Be sure to include a clear description of your changes and any relevant information for review.
We appreciate your contributions to making this project more robust and versatile! If you have any questions or need assistance, feel free to reach out to the project maintainers. Happy coding!

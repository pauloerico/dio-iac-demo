# Infrastructure as Code Demo
A simple Linux script demonstrating Infrastructure as Code (IaC).

## Task
Using bash script, automate the creation of the infrastructure as described below:

A company has 3 departments. It must be created directories, groups and users according to the scheme below.

![image](https://github.com/pauloerico/dio-iac-demo/assets/92192615/0627cdf2-85b8-4636-86bb-04b72ccc7f58)

- All the provisioning must be done in a bash file;
- The owner of all directories will be the root user;
- All users must have full access to the "publico" directory;
- The users of each group will have full access to their respective directories;
- Users shouldn't have any access to directories that don't belong to their departments, except "publico".

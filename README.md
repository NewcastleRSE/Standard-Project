[![unit tests - main branch](https://github.com/[Organisation]/[Repo]/actions/workflows/unitTests.yaml/badge.svg?branch=main)](https://github.com/[Organisation]/[Repo]/actions/workflows/unitTests.yaml)
[![e2e tests - main branch](https://github.com/[Organisation]/[Repo]/actions/workflows/e2eTests.yml/badge.svg?branch=main)](https://github.com/[Organisation]/[Repo]/actions/workflows/e2eTests.yml)
[![production build](https://github.com/[Organisation]/[Repo]/actions/workflows/prod.yaml/badge.svg?branch=main)](https://github.com/[Organisation]/[Repo]/actions/workflows/prod.yaml)

# Standard Project
A template repo for the standard RSE project

## >> INITIAL SETUP FOR NEW PROJECTS <<   

When you create a new project, we recommend that you do the following additional manual steps (and then delete this section of the readme).

- Add project details to  this Readme!

- Go to Settings -> Code security and Analysis and enable "Dependabot Version Updates". This will automatically create Pull Requests to keep your dependencies up-to-date. To activate this feature, you will need to specify the package ecosystem (i.e. NPM) and save the YML file. 

- Add a brief description of the project to the 'About' section (top right of this page). If your project involves a website, then add the URL here too.

## About

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sollicitudin ante at eleifend eleifend. Sed non vestibulum nisi. Aliquam vel condimentum quam. Donec fringilla et purus at auctor. Praesent euismod vitae metus non consectetur. Sed interdum aliquet nisl at efficitur. Nulla urna quam, gravida eget elementum eget, mattis nec tortor. Fusce ut neque tellus. Integer at magna feugiat lacus porta posuere eget vitae metus.

### Project Team

| Name  | Role | Affiliation
| ------------- | ------------- | ------------- |
| Firstname Lastname  | PI | Newcastle University  |
| Firstname Lastname | RSE  | Newcastle Universtiy  |

## Built With

This section is intended to list the frameworks and tools you're using to develop this software. Please link to the home page or documentation in each case.

[Framework 1](https://something.com)  
[Framework 2](https://something.com)  
[Framework 3](https://something.com)  

## Getting Started

### Prerequisites

Any tools or versions of languages needed to run code. For example, specific Python or Node versions. Minimum hardware requirements also go here.

### Installation

How to build or install the application.

### Running Locally

How to run the application on your local system. Examples of this would include `venv`, `anaconda`, `node`, `Docker` or `minikube`. 

### Running Tests

How to run tests on your local system.

## Deployment

Instructions on how to deploy to the staging or production systems. Examples of this would include cloud, HPC or virtual machine. Deployment should be done via GitHub Workflows but information on how these work and the different triggers should go here.

## Contributing

### Main Branch
Protected and can only be pushed to via pull requests. It should be considered stable and a representation of production code.

### Dev Branch
Should be considered fragile; code should compile and run, but features may be prone to errors.

### Feature Branches
A branch per feature that is being worked on.

https://nvie.com/posts/a-successful-git-branching-model/

## Acknowledgements
This work was funded by a grant from the UK Research Councils, EPSRC grant ref. EP/L012345/1, “Example project title, please update”.

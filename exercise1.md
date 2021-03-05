CI with Python

Flake8 is one of the linting tools for Python.

Python has a standard unit test library. There are also other testing libraries,
such as pytest for example.

For building the project Python uses CircleCI. In CircleCI you need to have a
.circleci folder in your repo. In that folder you need to have a configuration file
that tells all the steps that the build server needs to execute.

Some alternatives for Jenkins and GitHub actions are:
CircleCi, Azure Pipelines, Gitlab CI, Buildkite, Trello and Confluence.

Let’s consider whether to setup the application in a self-hosted or cloud-based environment.
Having 6 people working on the application means that it’s not propably a massive application
that would need a self-hosted environment. Using a cloud-based solution would propably make more sense.
This way the developers could concentrate more on the actual coding and not configuring,
maintaining and updating a self-hosted environment. On the other hand if the application goes viral
and attracts a lot of traffic then the cloud-based environment could become a limiting factor and
also very expensive since the billing is based on usage. One benefit of using a self-hosted
environment is that the required investment is known upfront when you buy and install the server yourself. 

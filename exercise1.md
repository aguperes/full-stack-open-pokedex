Here are some specific tools that can be used with Python:

- Linting: Flake8: “the wrapper which verifies pep8, pyflakes, and circular complexity “. It has a low rate of false positives.
- Testing: Pytest is a Python testing framework that originated from the PyPy project. It can be used to write various types of software tests, including unit tests, integration tests, end-to-end tests, and functional tests. Its features include parametrized testing, fixtures, and assert re-writing

Besides Jenkins and Github Actions, other options to set up a CI pipeline are:

- Bitbucket Pipelines. Additionally offers CD
- AWS CodePipeline.
- CircleCI. It can be hosted on-premise or used through a cloud offering
- Azure Pipelines
- GitLab
- Atlassian Bamboo. Whereas Bitbucket Pipelines is purely a cloud hosted option, Bamboo offers a self hosted alternative

Thinking about the hypothetical situation where there is a team of 6 people working on it, and not multiple teams, we could asume that it is a small to a medium project with no special requirements. Given that is the only information we have to make the assesment, we could say that the configuration of the application is simple and in order to avoid the hassle or the expense of setting up our own system, a cloud based environment might be cheaper.

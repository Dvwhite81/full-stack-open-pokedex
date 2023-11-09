I will be using Python as the coding language for these discussion points.

The linting tool I would choose to use for the project would either be Pylint, unless it needs to use strict formatting, in which case I would use Black. I've used Black before, but I understand that Pylint is much more configurable, but also more complex to understand.

For testing, the unittest module and Pytest seem similar to what we have done in FullStackOpen, and both are widely used in Python testing.

Some options to setup the CI, besides Jenkins and GitHub Actions, are:
CircleCI, GitLab CI, Atlassian Bamboo, JetBrains TeamCity, and BuildKite.

My main take-aways from researching the two options are:
Scaling up and down is very easy on a cloud server, and more difficult with local servers.
Cloud servers can be more secure or less secure, depending on the host.
Local power outages and hardware failures that would affect physical servers do not affect cloud servers, making them more reliable.
A disadvantage of using a cloud-based server would be the speed, as it can be slower.

All in all, I think a cloud-based environment would be better than a self-hosted environment for this project, unless the project is very complex and could cause a slow-down or security is a main priority.

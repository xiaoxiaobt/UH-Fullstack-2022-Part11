# Exercise 1

The language of choice is Python 3, and the scenario can be a full stack project with Flask.

- Linting: `autopep8` is a really popular package that does linting for Python codes, however, there are many other linting tools available on the Internet (for instance, `black`).
- Testing: `pytest` is a popular unit testing framework for Python, and there are also many other tools available. For a website, end-to-end testing is also required, so `cypress` for instance can also be considered as a good choice.
- Building: Because Python 3 is not a compiled language, typically it does not require the building stage to distribute the binaries. However, as a Flask project, the production build of the website can be build to a WSGI distribution file.

For CI/CD pipelines, there are many other alternatives. GitLab offers similar CI/CD pipelines when comparing to GitHub, Travis CI also offers CI/CD pipelines. There are also project specific CI/CD (for instance, TeamCity for IntelliJ projects) available.

Depending on the use case as well as the type of project (open-source / private), the best choice can be very different. For commercial projects, the best choice is to use a self-hosted solution to ensure that the project always have access to dedicated resources and possibly extra resources (e.g. GPUs), and at the same time, the information security is ensured. For open-source projects, cloud-based project can be more convenient, cost-efficient, and easy to use.

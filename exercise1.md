Here are some considerations for a CI of Python application being developed by a team of six people.

For the CI/CD process we will need a linting tool for maintaining code quality, we could use something like Pylint. We also need a testing tool, that ensures our code is robust, we could use a framework like pytest. We will also need a building tool, for python this is not that much necessary, but, we could use a packaging tool like poetry to handle dependency management.

As to some alternatives to CI/CD tools outside of Jenkins and GitHub Actions, we could use:
- **CircleCI**: Offers a flexible cloud-based CI/CD system.
- **Travis CI**: A simple-to-use CI tool often used in open-source projects.
- **Drone CI**: A modern, container-based CI/CD system.

Because we have a relative small team, it is best to use a cloud-based solution like GitHub Actions. As it provides a easier setup, while providing scalability and minimal maintenance. Also, because we have a small team, the cloud-based option will probably be cheaper.

To make a better decision, I’d need information about:
- Budget constraints
- Data security policies
- Team's expertise in managing infrastructure
- Expected frequency and volume of CI builds

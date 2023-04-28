# Contributing <!-- omit in toc -->

Please take the time to read and understand the contribution guide before
creating an issue or pull request.

- [Code of Conduct](#code-of-conduct)
- [Contribution Guidelines](#contribution-guidelines)
  - [Reporting Issues/Bugs](#reporting-issuesbugs)
- [Maintainership](#maintainership)
- [Best Practices](#best-practices)
    - [Tests](#tests)
    - [Backward Compatibility](#backward-compatibility)
    - [Documentation](#documentation)

## Code of Conduct

Please read our [Code of Conduct](./CODE_OF_CONDUCT.md) to keep our open-source
community approachable and respectable.

## Contribution Guidelines

Contributions to projects can be in the form of bug reports or feature requests
via issues or pull requests. Pull requests are the preferred method of
contribution to a project.

### Reporting Issues/Bugs

Issues are the best way to file a bug report for a project. Before filing an
issue, please check for the following:

- Attempt to replicate your problem to ensure it can be repeated and isn't
  coincidental.
- Ensure that your feature request is within the scope of the project. For
  example, please don't suggest adding Drupal support to a WordPress plugin. If
  you are unsure, try making a discussion post in the project to ask the project
  maintainers.
- Search the repository for an existing issue/pull request to your issue/feature
  request. Check to make sure that your issue wasn't already reported/requested.

## Maintainership

All repositories should have a
[CODEOWNERS](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)
file included with a specified owner for the project. Preferably a team or 2+
individuals would be marked as "owners" who are responsible for the project.
These owners are responsible for the maintainership of the project and
controlling the scope of features within the said project. They shall have the
final say on whether or not a feature request is a good fit for the scope of a
project.

## Best Practices

The following are some best practices that we strive for in all of our projects.
A project may override these where it makes sense. The respective project should
have an updated `CONTRIBUTING.md` included with information about best practices
for the project.

#### Tests

Contributions to projects should have tests associated with them. Failure to
include tests could result in your contribution being declined.

#### Backward Compatibility

All contributions must be backward compatible unless a breaking change is being
made intentionally. Breaking changes must follow [semantic
versioning](https://semver.org/) and publish a new major release with a call out
to the breaking change in the project's CHANGELOG.

#### Documentation

Ensure that the `README.md`, `CHANGELOG`, and any other documentation are
up-to-date with any changes made.

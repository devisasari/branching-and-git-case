# Branching & Git Case

- This is the Branching & Git Case, a project given by the Young Coders Club (Havas CX).

## About Case Study

You are leading a team where you should build a
website for an e-commerce company. 2 teams are
working in different parts of the code development,
separated as frontend and backend. The company
decides to have all the development in one
repository. They provided 3 environments called
dev, staging and production. They would like to
know how branching strategy will work and how
should the CI/CD be set up? (i.e which branches
should be connected to the environments)

## Completion of Case

### Branching Strategy

1. Create a ‘master’ branch in the repository. This
branch will be used to deploy the code to the
production environment.
2. Create a ‘dev’ branch in the repository. This
branch will be used to deploy the code to the
development environment.
3. Create a ‘staging’ branch in the repository. This
branch will be used to deploy the code to the
staging environment.
4. Create a ‘feature’ branch for each feature that
you are developing. This branch should be
branched off from the ‘dev’ branch.
5. When a feature is complete, it should be merged
into the ‘dev’ branch.
6. When the code is ready for testing, it should be
merged into the ‘staging’ branch.
7. When the code is ready for release, it should be
merged into the ‘master’ branch.

### CI/CD Setup

1. Set up a Continuous Integration (CI) server to
monitor the repository.
2. Set up a Continuous Delivery (CD) server to
deploy the code to the different environments.
3. Set up rules to deploy the code to the different
environments.
4. Set up automated tests to ensure that the code is
of high quality.
5. Set up automated alerts to notify the team of any
issues.

### Examples

a. The ‘master’ branch should be connected to the
production environment.

b. The ‘staging’ branch should be connected to the
staging environment.

c. The ‘dev’ branch should be connected to the
development environment.

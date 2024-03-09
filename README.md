# ConventionalCommits.org

[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org)

This repository is the home of the Conventional Commits specification.

## Repository Layout

We use [HUGO](https://gohugo.io/) as a static site generator, so we follow the [directory structure](https://gohugo.io/getting-started/directory-structure/) proposed by HUGO.

#### Our Implementation

- `./content`: contains all the versions of the specification.
- `./content/next/`: contains the version of the specification (where all the changes SHOULD be made).
- `./content/**/index.[lang].md`: contains the content of the specification; if a language is specified, it's a translation.

## Contributing

We'd love your help refining the language of this specification, fixing typos, or adding more translations. Please don't hesitate to send a pull request.

### Adding a Translation

1. Create a new file in `./content/version/index.[lang].md` using the Hugo command `hugo new [version]/index.[lang].md`.
2. Ensure all files have the appropriate fields required (see others as an example).
3. Add the language to the `config.yaml` file (see others as an example).

### Running the Project Locally

There's a `docker-compose.yml` file ready that will help you check if the website looks good!
To run it, make sure you have [docker-compose installed](https://docs.docker.com/compose/install/#install-compose) on your machine and just use the command `docker-compose up` to make it run locally.

Once the website is compiled, you can see the website by visiting `http://localhost:1313`

## Badges!

Tell your users that you use the Conventional Commits specification:

```markdown
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org)

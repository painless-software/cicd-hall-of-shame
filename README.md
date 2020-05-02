CI/CD Hall Of Shame
===================

Educational examples of CI/CD pipeline implementations,
implementation patterns you should not follow.

Show-cased Patterns (Violations)
--------------------------------

- Copy and paste (DRY)
- Comments, excessive comments (self-explanatory code)
- Install tools on-the-fly (install once, use often)
- Spaghetti code (favor declarative over functional)
- Create results dynamically (use version control)

Disclaimer
----------

All similarities with living people and projects is unintentional,
all code is and show-cased approaches are fictitious. No animals
were harmed in the production of this code repository.

Public examples
---------------

Some repositories that showcase issues and/or solution approaches.

- Matrix dependencies that expand:
  - [imperative](
    https://gitlab.com/StanfordLegion/legion/blob/master/.gitlab-ci.yml) vs [declarative](
    https://gitlab.com/StanfordLegion/legion/blob/master/.travis.yml) ([author's explanation](
    https://gitlab.com/gitlab-org/gitlab/issues/15356#note_272255100))
- Pipelines you can't run locally:
  - [Symfony](https://github.com/symfony/symfony/blob/master/.travis.yml)

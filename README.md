# Starfish Bioscience — organisation defaults

Default community health files for every repository of the organisation that does not define its
own:

- `.github/ISSUE_TEMPLATE/`: issue forms for the five organisation issue types — **Bug**,
  **Feature**, **Task**, **Research** (an exploratory scientific investigation) and **Run**
  (running or re-running a pipeline on a dataset). Each form sets the issue type and adds the
  issue to the organisation's shared project; blank issues are disabled;
- `.github/pull_request_template.md`: pull request template.

A repository with its own `.github/ISSUE_TEMPLATE/` or pull request template uses those instead.

This repository is public, as GitHub requires for organisation defaults: it only contains generic
templates. Changes are made in the team's internal configuration repository and copied here.

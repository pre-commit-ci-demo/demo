[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/pre-commit-ci-demo/demo/main.svg)](https://results.pre-commit.ci/latest/github/pre-commit-ci-demo/demo/main)
[![Build Status](https://github.com/pre-commit-ci-demo/demo/workflows/pre-commit/badge.svg)](https://github.com/pre-commit-ci-demo/demo/actions)
[![Build Status](https://travis-ci.com/pre-commit-ci-demo/demo.svg?branch=main)](https://travis-ci.com/pre-commit-ci-demo/demo)
[![Build Status](https://dev.azure.com/precommitci/pre-commit-ci-demo/_apis/build/status/pre-commit-ci-demo.demo?branchName=main)](https://dev.azure.com/precommitci/pre-commit-ci-demo/_build/latest?definitionId=2&branchName=main)
[![Build status](https://ci.appveyor.com/api/projects/status/109wuvh6tmcys06u/branch/main?svg=true)](https://ci.appveyor.com/project/pre-commit-ci-bot/demo/branch/main)
[![pipeline status](https://gitlab.com/pre-commit-ci-bot/demo/badges/main/pipeline.svg)](https://gitlab.com/pre-commit-ci-bot/demo/-/commits/main)
[![CircleCI](https://circleci.com/gh/pre-commit-ci-demo/demo/tree/main.svg?style=svg)](https://circleci.com/gh/pre-commit-ci-demo/demo/tree/main)

demo
====

comparing pre-commit.ci against a bunch of other ci providers

### results

_last tabulated on 2020-12-15_

runs are averaged over 5 pull requests.  timing starts on PR creation.

![chart comparing seconds to complete](./img/2020-12-15_noop.svg)

note: gitlab took much longer to complete so it is on a separate graph:

![chart comparing seconds to complete w/ gitlab](./img/2020-12-15_noop-gitlab.svg)

the raw data is available [here](./data/2020-12-15_noop.tsv)

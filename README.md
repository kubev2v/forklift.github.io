<img src="img/forklift-logo-lightbg.svg" alt="Logo" width="100" />

# Forklift

Welcome to the Forklift repository. Forklift is part of the [Konveyor](https://www.konveyor.io/) project.

## About Konveyor
[Konveyor](https://www.konveyor.io/) is a community of people passionate about helping others modernize and migrate their applications to the hybrid cloud by providing tools to accelerate rehosting, replatforming, and refactoring their applications to run on Kubernetes.

## About Forklift

Forklift is an open-source tool for the large-scale migration of virtual machines to KubeVirt.
The source for virtual machines initially is VMware vSphere 6.x, extending the reach progressivley to oVirt / RHV, and OpenStack. 

## Forklift projects

* [Forklift Operator](https://github.com/konveyor/forklift-operator). The Forklift Operator deploys and maintains Forklift.
* [Forklift Documentation](https://github.com/konveyor/forklift-documentation). Documentation for installing and using Forklift.
* [Forklift UI](https://github.com/konveyor/forklift-ui). The Forklift UI is based on [Patternfly 4](https://www.patternfly.org/v4/).
* [Forklift Controller](https://github.com/konveyor/forklift-controller). The Forklift Controller orchestrates the migration.
* [Forklift Validation](https://github.com/konveyor/forklift-validation). The Forklift Validation service checks the virtual machines for possible issues before migration. Runs with [Open Policy Agent](https://www.openpolicyagent.org/).
* [Forklift `must-gather`](https://github.com/konveyor/forklift-must-gather). Support tool for gathering information about the Forklift environment.

## Engage

* [Discussion group for Forklift](https://groups.google.com/g/forklift-dev)

# Forklift GitHub pages repo

This repository holds the code that generates the [Forklift Project's web page](https://forklift.konveyor.io/).

For more information refer [GitHub Pages Guide to Using Jekyll](https://help.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll).

## Contributing

1. If making changes to typescript files please run `yarn run build && yarn run bundle` to build typescript and update the bundle.
2. Do `git add -A` **AFTER** generating the bundle to add the bundle to the commit.

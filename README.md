# casc-mc-cloudbees-ci-eks-addon

[![gitleaks badge](https://img.shields.io/badge/protected%20by-gitleaks-blue)](https://github.com/zricethezav/gitleaks#pre-commit) [![gitsecrets](https://img.shields.io/badge/protected%20by-gitsecrets-blue)](https://github.com/awslabs/git-secrets)

This repository is for [Configuration as Code (CasC) for controllers](https://docs.cloudbees.com/docs/cloudbees-ci/latest/casc-controller/).

Plugins and plugin catalogs are curated with the [CloudBees CasC Plugin Catalog and Transitive Dependencies Calculator](https://github.com/kyounger/casc-plugin-dependency-calculation).

Inheritance merge strategies are explained in the [CloudBees CI documentation](https://docs.cloudbees.com/docs/cloudbees-ci/latest/casc-controller/advanced#_configuring_bundle_inheritance_with_casc).

This bundle is tested and validated against the `chart` version from the `main.yaml` in [CloudBees CI add-on for Amazon EKS blueprints](https://github.com/cloudbees/terraform-aws-cloudbees-ci-eks-addon).

# GitHub Actions Examples

Here you will find some handy examples for CICD automations using GH actions


## NPM

Automate NPM operations

### Auto Publish Component/Package

[This pipeline](npm-auto-publish-to-gh-packages.yaml) automatically publish a
new package version when the next conditions are met:

- Push to develop branch
- The version in `./package.json` is different from the last one published

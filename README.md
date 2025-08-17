## Overview

This repository contains reusable GitHub Actions workflows for common tasks such as building, testing, deploying, and releasing projects. The workflows are written in YAML and can be adapted for different applications.

## Workflows

| File                                | Description                                   |
|-------------------------------------|-----------------------------------------------|
| auto-merge.yml                      | Merges the develop branch into prod           |
| build-deploy-jekyll-gh-pages.yml    | Builds and deploys Jekyll to GitHub Pages     |
| deploy-laravel-shared-hosting.yml   | Deploys Laravel applications to shared hosting|
| deploy-nextjs-static-to-server.yml  | Deploys a static Next.js build to a server    |
| release.yml                         | Creates GitHub releases                       |
| test-laravel.yml                    | Runs PHPStan and PHPUnit tests for Laravel    |

## Notes

- All workflows are written in YAML.
- `.gitattributes` is used to specify file handling for YAML files.

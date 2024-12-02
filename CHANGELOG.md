# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- This CHANGELOG file.
- Kubernetes manifest files for running EF-API in the production instance. [#72](https://github.com/htrc/torchlite-app/issues/72)

### Changed
- Backend cache expiration time in the development instance to 3600 seconds (1 hour). [#7](https://github.com/htrc/torchlite-argocd/issues/7)
- Kubernetes manifest files for running TORCHLITE backend and frontend applications in the production instance. [#73](https://github.com/htrc/torchlite-app/issues/73)
- Added credentials for mutual TLS with registry to dev deployment for backend to support direct communication. [#125](https://github.com/htrc/torchlite-backend/issues/125)
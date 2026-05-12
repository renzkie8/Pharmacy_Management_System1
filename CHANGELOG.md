# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2026-05-12] - Milestone: SimpliShop Migration & Azure Deployment
### Added
- [Carl Renz M. Colico & Francis Gabriel Nonato] - Migrated project from Pharmacy Management System to SimpliShop (Static Web App).
- [Carl Renz M. Colico & Francis Gabriel Nonato] - Created Azure App Service `SimpliShop-System` on Python 3.11 runtime.
- [Carl Renz M. Colico & Francis Gabriel Nonato] - Implemented FastAPI `app.py` to serve static HTML/CSS/JS content.
- [Carl Renz M. Colico & Francis Gabriel Nonato] - Established GitHub Actions CI/CD pipeline for automated deployments (Optimization 1).

### Changed
- [Carl Renz M. Colico & Francis Gabriel Nonato] - Renamed repository from `Pharmacy-Management-System` to `SimpliShop`.
- [Carl Renz M. Colico & Francis Gabriel Nonato] - Updated Azure Federated Credentials to support renamed repository.
- [Carl Renz M. Colico & Francis Gabriel Nonato] - Optimized App Service startup command for Uvicorn compatibility.

### Fixed
- [Carl Renz M. Colico & Francis Gabriel Nonato] - Resolved "Internal Server Error" by adding explicit startup command in Azure Configuration.
- [Carl Renz M. Colico & Francis Gabriel Nonato] - Fixed threading casing issues (`t.start()`) across all service modules.

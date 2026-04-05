# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.1] - 2026-04-05

### Added
- `description` field on all 16 operations (resolves Spectral `operation-description` warnings)
- `contact` field in `info` object (resolves Spectral `info-contact` warning)

## [1.0.0] - 2026-04-04

### Added
- OpenAPI 3.1.0 spec with auth, categories, and transactions endpoints
- JWT Bearer security scheme (global, except auth endpoints)
- RFC 7807 Problem+JSON error responses
- Separate Write/Update schemas for clean POST/PUT/PATCH semantics
- Pagination with limit/offset on list endpoints
- TypeScript axios client generation config (GitHub Packages)
- Java Spring Boot 3 server stubs generation config (GitHub Packages)
- Swift 5 URLSession client generation config (Swift Package Manager)
- GitHub Actions: spec validation on PRs, publish on version tags

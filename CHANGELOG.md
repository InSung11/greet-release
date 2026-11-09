# Changelog

All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2026-11-09

### Added
- Add `greet(name, punctuation="!")`: fixed `!` ending → configurable punctuation, preserving `!` by default.

### Fixed
- Fix `greet(name)` for empty or whitespace-only names: blank greeting → `Hello, world!` with default punctuation.

## [0.1.0] - 2026-11-09

### Added
- Add `greet(name)` and command-line greetings: no greeting API or CLI → `Hello, <name>!`, with CLI default `world`.

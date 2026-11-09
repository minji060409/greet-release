# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2026-11-09

### Added

- `greet()`: `punctuation` 인수를 추가하여 끝맺음 부호를 변경할 수 있도록 지원(기본값 `!`).

### Fixed

- `greet()`: 빈 문자열 또는 공백 입력 시 기존 빈 인사말(`Hello, !`) 대신 `world`를 사용하도록 수정.

## [0.1.0] - 2026-11-09

### Added

- `greet()` 함수 및 명령행 인사말 실행 기능
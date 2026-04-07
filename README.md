# GClientSo

GClientSo is a lightweight repository for storing client-side shared object artifacts and build metadata.

## Contents

- `libs/` - Native library artifacts for supported ABIs.
  - `arm64-v8a/` - ARM64 shared object builds.
- `libs/BUILD_INFO.txt` - Build metadata including build date, type, commit SHA, and changelog.

## Getting Started

This repository is primarily a binary artifact store rather than a source-based project. Use the included native libraries as needed in your client integration.

## Build Metadata

The `libs/BUILD_INFO.txt` file contains the latest build information for the artifacts in this repository.

## License

This project is licensed under the terms defined in `LICENSE`.

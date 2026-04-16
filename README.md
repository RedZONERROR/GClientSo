# GClientSo

GClientSo is a lightweight repository for storing client-side shared object artifacts and build metadata.

## Contents

- `libs/` - Native library artifacts for supported ABIs.
  - `arm64-v8a/` - ARM64 shared object builds organized by package name.
    - `{package-name}/` - Package-specific libraries.
      - `*.so` - Library files.
      - `BUILD_INFO.txt` - Build metadata for this package.
- `apps.json` - Application configuration and metadata.

## Getting Started

This repository is primarily a binary artifact store rather than a source-based project. Use the included native libraries as needed in your client integration.

## Build Metadata

Each package has its own `BUILD_INFO.txt` file containing build information:
- Example: `libs/arm64-v8a/{package-name}/BUILD_INFO.txt`

The BUILD_INFO.txt file contains:
- Build date
- Build type
- Commit SHA
- Commit message
- Repository information
- Workflow run details

## License

This project is licensed under the terms defined in `LICENSE`.

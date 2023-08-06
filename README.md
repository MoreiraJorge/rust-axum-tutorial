# Rust Axum REST API tutorial

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/rust%20-%2343853D.svg?&style=for-the-badge&logo=rust&logoColor=white&color=eb7734" alt="Rust" /></a>
  <a href="#"><img src="https://img.shields.io/badge/axum%20-%23007ACC.svg?&style=for-the-badge&logo=axum&logoColor=white&color=dbeb34" alt="Axum" /></a>
  <a href="#"><img src="https://img.shields.io/static/v1?message=Tokio&logo=&labelColor=5c5c5c&color=b00bd9&logoColor=white&label=%20&style=for-the-badge&logo=appveyor"></a>
</p>

This is a simple REST API written in Rust using the [Axum](https://github.com/tokio-rs/axum) web framework. All credits goes to [Jeremy Chone](https://www.youtube.com/@JeremyChone) with his awesome [tutorial](https://www.youtube.com/watch?v=XZtlD_m59sM).

This tutorial is divided into 3 parts:

- Beginner:
  - First route Hello World
  - Quick Dev Setup
  - Hello Params / Path
  - Static file router
- Intermediate:
  - Api login
  - Resposne Mapper layer
  - Cookies
  - Model for CRUD operations
  - API routes
- Advanced:
  - Custom auth middleware
  - Custom extractor (Ctx)
  - Ctx from REST to CRUD model api
  - Optimisations on Ctx middleware
  - Advance error handling (Client vs Server)
  - Logging

## Notes

Execute the following command to run the dev test:

```bash
cargo watch -q -c -w tests/ -x "test -q quick_dev -- --nocapture"
```

Execute the following command to run the api:

```bash
cargo watch -q -c -w src/ -x run
```

Also the course code is available [here](https://github.com/jeremychone-channel/rust-axum-course).

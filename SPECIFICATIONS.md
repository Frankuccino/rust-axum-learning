# Course Specifications

This learning journey is based on the **Axum Full Course**:  
https://github.com/aarambh-darshan/axum-full-course

It tracks learning through notes, distilled lessons, and practical experiments.

---

## Rust Environment

- **Rust version**: 1.72+ (latest stable at the time of learning)
- **Toolchain**: stable-aarch64-apple-darwin (default)
- **Installed targets**: aarch64-apple-darwin
- **Cargo version**: 1.72+

---

## Frameworks and Libraries

| Crate / Tool       | Version | Notes / Features                |
| ------------------ | ------- | ------------------------------- |
| axum               | 0.8.x   | Core web framework              |
| axum-extra         | 0.10.x  | Typed-header, query, multipart  |
| tokio              | 1.x     | Full async runtime              |
| sqlx               | 0.8.x   | Postgres + uuid + chrono        |
| tracing            | 0.1     | Logging / tracing               |
| tracing-subscriber | 0.3     | Env filter, JSON output         |
| jsonwebtoken       | 9.x     | JWT authentication              |
| argon2             | 0.5     | Password hashing                |
| serde              | 1.x     | Serialization / deserialization |
| serde_json         | 1.x     | JSON handling                   |
| dotenvy            | 0.15    | Environment variable management |

---

## Development Environment

- **OS**: macOS
- **Editor / IDE**: VSCode
- **Terminal / Shell**: iTerm2 (zsh)

---

## Notes

- This repository does **not include course source code**, only personal notes, lessons, and experiments.
- All experiments are tested against the versions listed above.
- Reproducibility is tied to these versions; later major updates may require adjustments.

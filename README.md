# Rust-Webserver

A lightweight HTTP web server implemented in Rust, designed for educational purposes and to demonstrate fundamental networking concepts without relying on external frameworks.

## 🚀 Features

- **Pure Rust Implementation**: Built using Rust's standard library, ensuring safety and performance.
- **Static File Serving**: Serves static HTML files, such as `hello.html`.
- **Custom 404 Page**: Provides a user-friendly `404.html` for undefined routes.
- **Minimal Dependencies**: No external crates used, offering a clear view of underlying mechanisms.

## 🛠️ Getting Started

### Prerequisites

- Rust installed on your system. If not, download it from [rust-lang.org](https://www.rust-lang.org/tools/install).

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/kollisaivenu/Rust-Webserver.git
   cd Rust-Webserver

2. **Build the Project**:

   ```bash
   cargo build --release

3. **Run the Server**:

   ```bash
   cargo run

By default, the server listens on `127.0.0.1:7878`.
# rust_cli_pass_manager
Simple cli password manager without database written in rust

# Usage
```
Usage: cli_pass_manager --login <LOGIN> --password <PASSWORD>

Options:
  -l, --login <LOGIN>        адрес / уникальный идентификатор сайта
  -p, --password <PASSWORD>  мастер пароль
  -h, --help                 Print help
  -V, --version              Print version
```

# Run and build
``` bash
git clone https://github.com/nkeff/rust_cli_pass_manager
```

### Run
``` bash
cargo run
```

### Build
``` bash
cargo build -r
```

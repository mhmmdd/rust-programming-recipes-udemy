`$ cargo run -- --help`\
`$ cargo run -- hello.world`\
`$ cargo run -- test_data/hello.md`\

## For maud install nightly rust
`$ rustup install nightly`\
`$ cargo +nightly run -- test_data/hello.md`\
`$ rustup override set nightly`\
`$ cargo run -- test_data/hello.md -w --css foo.css`\
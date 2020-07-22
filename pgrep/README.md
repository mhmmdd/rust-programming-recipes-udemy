`$ cargo run -- Hello -f test_data/t1.txt`


## To see the errors
`$ cargo run`
error: The following required arguments were not provided:
    <pattern>

USAGE:
    pgrep.exe [OPTIONS] <pattern>

`$ cargo run Hello`
Error: ArgErr { arg: "file" }
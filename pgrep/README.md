`$ cargo run -- Hello -f test_data/t1.txt`


## To see the errors
`$ cargo run`
error: The following required arguments were not provided:
    <pattern>

USAGE:
    pgrep.exe [OPTIONS] <pattern>

`$ cargo run Hello`
Error: ArgErr { arg: "file" }


`$ cargo run -- Hello -f test_data`
    Finished dev [unoptimized + debuginfo] target(s) in 0.13s
     Running `target\debug\pgrep.exe Hello -f test_data`
"test_data\\t1.txt"
[Record { line: 1, text: "Hello world" }, Record { line: 3, text: "Hello People of te world" }, Record { line: 5, text: "Lets all say Hello" }]
"test_data\\t2.txt"
[Record { line: 2, text: "I\'m going to say Hello" }, Record { line: 4, text: "People will say Hello back" }]
Ok(())

`$ cargo run -- Hello -f test_da`
Err(Os { code: 2, kind: NotFound, message: "The system cannot find the file specified." })
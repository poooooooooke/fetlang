# Fetlang
Fetlang is a statically typed, procedural, esoteric programming language and
reference implementation. It is designed such that source code looks like
poorly written fetish erotica  

Fetlang is not recommended for production use at this moment, especially in
medical or military applications

## Example
The following example outputs the arguments given to the executable:

    Make Betty moan
    Worship Carrie's feet
    
    Bind Amy to Saint Andrew's Cross
        Have Amy hogtie Betty
        If Amy is Carrie's bitch
            Make Slave scream Betty's name
            Make Betty moan


## Features
* Input/output with standard streams and files
* Statically typed
* Gendered variables
* Access previously mentioned variables using pronouns
* Numbers represented internally as fractions instead of floating point
* Transpiles to C
* Case insensitive
* Confusing English-like syntax and unhelpful error messages
* Probably Turing complete
* Extensible - just install your fetish in share/fetlang/fetishes

## Building
Requirements:
* meson
* ninja
* gcc/g++(>=4.9) or clang(>=3.5)  

Optional Dependencies:
* boost algorithm(>=1.62)
* boost filesystem(>=1.62)
* boost system(>=1.62)

Supported systems:  
* macOS (tested with Travis CI)
* GNU/Linux (tested with Travis CI)
* Other modern Unix-like systems

Build Fetlang:  
```shell
$ git clone https://github.com/Property404/fetlang
$ cd fetlang
$ meson --buildtype=release src build
$ cd build
$ # Build Fetlang
$ ninja
$ # Run unit tests
$ ninja test
```

Install Fetlang:  
```shell
$ sudo ninja install
$ # Make sure it worked
$ fetlang ../examples/hello.fet && ./a.out
Hello World!
```

## Documentation
[Comments](docs/comments.md)  
[Control Flow](docs/control%20flow.md)  
[Fetishes](docs/fetishes.md)  
[Fetish Reference](docs/reference.md)  
[Grammar](docs/grammar.md)  
[Tutorial](docs/tutorial.md)  
[Types](docs/types.md)  
[Variables](docs/variables.md)  

## License
Fetlang is licensed under the BSDM (BSD, modified) license


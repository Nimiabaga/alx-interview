
# 0x06. Star Wars API

## Description
This project involves interacting with the Star Wars API to fetch and display information about characters from a specific Star Wars movie. The movie ID is provided as an argument, and the script retrieves the names of all characters appearing in that movie.

## Learning Objectives
- How to make HTTP requests in JavaScript using `request` or `fetch`.
- Working with RESTful APIs.
- Handling asynchronous operations using callbacks, promises, and `async/await`.
- Parsing and manipulating JSON data.
- Using command-line arguments in Node.js.
- Iterating over arrays and manipulating data structures in JavaScript.

## Requirements
- All scripts should be interpreted on Ubuntu 20.04 LTS using Node.js (version 10.14.x).
- Code must be semistandard compliant with semicolons.
- You are not allowed to use `var`; use `const` or `let` instead.
- A `README.md` file is mandatory.
- All files should be executable and end with a new line.
- All scripts should have a shebang `#!/usr/bin/node`.

## Installation
To install Node.js version 10, run the following commands:
```bash
$ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
$ sudo apt-get install -y nodejs
```

## Usage
To run the script, use the following command:
```bash
$ ./<script_name> <movie_id>
```

## Example
```bash
$ ./0-starwars_characters.js 1
Luke Skywalker
C-3PO
R2-D2
...

$ ./0-starwars_characters.js 4
Luke Skywalker
Leia Organa
Darth Vader
...
```

## Author
Julie Peters ..

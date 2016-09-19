[![Build Status](https://travis-ci.com/KCreate/interpreter-testing.svg?token=yitMwy9Lg5peiAqCZjoK&branch=master)](https://travis-ci.com/KCreate/interpreter-testing)

# The __Charly__ programming language interpreter

This is my try at writing an interpreter of a dynamic language from scratch with my bare hands.

# Syntax
TODO

# CLI options
```
ruby main.rb filename [options...]

<options>
 --log              # Display logging info
 --ast              # Display the abstract syntax tree
 --tokens           # Display a list of tokens found by lexical analysis
 --noexec           # Don't execute the program
 --noopt            # Skip the structurization step in the parser (useful for debugging)
 --nometa           # Hide meta info in the abstract syntax tree
 --noprelude        # Don't load the prelude file
 --nodeproductions  # Display realtime-information about nodes being produced (laggy af)
 --dump-ast-json    # Dump the Abstract Syntax Tree of all programs in a file called AST.#{filename}.json inside the parser-dump directory
```

# Contributors
- [KCreate - Leonard Schütz](https://github.com/KCreate)

# Inspired by
- Javascript
- C

# License
The MIT License (MIT)
Copyright (c) <2016> Leonard Schütz

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
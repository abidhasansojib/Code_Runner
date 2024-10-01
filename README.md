# Universal Code Runner

This Bash script (`run`) allows you to run a variety of programming languages using a single command. It identifies the programming language based on the file extension and executes the code accordingly. It supports 65 different programming languages, making it a versatile tool for developers working with multiple languages.

## Features
- Automatically detects the programming language based on the file extension.
- Supports both compiled and interpreted languages.
- Simple to use with a single command.
- Runs the output binary or script in the same terminal.

## Supported Languages

The following programming languages and file extensions are supported:

1. **C++** (`.cpp`)
2. **C** (`.c`)
3. **Python** (`.py`)
4. **Java** (`.java`)
5. **JavaScript** (`.js`)
6. **TypeScript** (`.ts`)
7. **PHP** (`.php`)
8. **Go** (`.go`)
9. **Rust** (`.rs`)
10. **Swift** (`.swift`)
11. **Haskell** (`.hs`)
12. **Kotlin** (`.kt`)
13. **Ruby** (`.rb`)
14. **Perl** (`.pl`)
15. **R** (`.r`)
16. **Lua** (`.lua`)
17. **Dart** (`.dart`)
18. **Scala** (`.scala`)
19. **Objective-C** (`.m`)
20. **F#** (`.fs`)
21. **Elixir** (`.exs`)
22. **Zsh** (`.zsh`)
23. **Julia** (`.jl`)
24. **Lisp** (`.lisp`, `.cl`)
25. **OCaml** (`.ml`)
26. **Clojure** (`.clj`)
27. **Erlang** (`.erl`)
28. **Nim** (`.nim`)
29. **V** (`.v`)
30. **Crystal** (`.cr`)
31. **Fortran** (`.f90`, `.f95`)
32. **COBOL** (`.cob`, `.cbl`)
33. **Pascal** (`.pas`)
34. **Vala** (`.vala`)
35. **Prolog** (`.pl`)
36. **Tcl** (`.tcl`)
37. **Scheme** (`.scm`)
38. **Forth** (`.fs`)
39. **Awk** (`.awk`)
40. **Makefile** (`.mk`)
41. **Matlab/Octave** (`.m`)
42. **Groovy** (`.groovy`)
43. **Ada** (`.adb`)
44. **Solidity** (`.sol`)
45. **Verilog** (`.v`)
46. **VHDL** (`.vhdl`)
47. **Racket** (`.rkt`)
48. **Red** (`.red`)
49. **XSLT** (`.xslt`)

## Prerequisites

Before using the script, ensure the required compilers/interpreters for the languages you want to run are installed. For example:
- `g++` for C++
- `gcc` for C
- `python3` for Python
- `node` for JavaScript
- And so on...

You can install them via your system’s package manager like `apt`, `brew`, or `yum` depending on your OS.

## Installation

1. Download the `run` script.
2. Move it to a directory in your `PATH` so you can execute it globally:
   ```bash
   mv run /usr/local/bin/
   chmod +x /usr/local/bin/run
3. Ensure that /usr/local/bin/ is part of your system’s PATH.

# Usage
<p>To run any supported program, use the following command:</p>
```bash
echo "run <filename>"
  
<p>For example:</p>
```bash
echo "run hello.cpp"

<p>This will compile and run hello.cpp, and the output file will be named hello.</p>
# Error Handling

<p>If an error occurs during compilation or execution, the script will print an error message indicating the problem.
</p>
# Output

<p>For compiled languages (like C, C++, Rust, etc.), the output binary will be named after the input file (without the extension). For example, hello.cpp will produce an output file named hello, which the script will execute automatically.</p>

# Example Usage

1. Run a C++ program:
   ```bash
   echo "run program.cpp"

2. Run a Python script:
   ```bash
   echo "run script.py" 


# Extending the Script

<p>If you need to add support for additional languages, modify the case block in the script by adding new file extensions and the corresponding commands to run those programs.</p>

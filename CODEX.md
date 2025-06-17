# STD Covenant Coding Standards

A covenant of consistent coding practices, naming conventions, and abbreviations for accessible and maintainable development.

## Table of Contents

- [General Abbreviations](#general-abbreviations)
- [Math](#math)
- [File Naming Convention](#file-naming-convention)

## Abbreviations

### General

- `arr` - array
- `idx` - index
- `rec` - recursion
- `iter` - iteration
- `val` - value
- `mid` - middle
- `tmp` - temporary
- `bin` - binary
- `ll` - linked list
- `res` - result
- `ans` - answer
- `err` - error
- `var` - variable
- `ovf` - overflow
- `num` - number
- `rand` - random
- `std` - standard
- `vec` - vector
- `lvl` - level
- `obj` - object
- `ref` - reference
- `cfg` - config
- `config` - configuration
- `io` - I/O (Input/Output)
- `hi` - high
- `lo` - low
- `in` - input
- `out` - output
- `int` - integer
- `exec` - execute
- `exe` - executable
- `lang` - language
- `eval` - evaluate
- `char` - character
- `attr` - attribute
- `comp` - component or compile
- `cmp` - comparison
- `src` - source
- `dist` - distribution or distance
- `fn` or `func` - function
- `prev` - previous
- `pub` - public
- `const` - constant
- `env` - environment
- `fmt` - format
- `buf` - buffer
- `undef` - undefined
- `def` - define or definition
- `proto` - prototype or protocol
- `gen` - generate
- `curr` - current
- `utils` - utilities
- `glob` / `globs` - global(s)
- `init` - initialize or initialization
- `bench` - benchmark
- `deps` - dependencies
- `dev` - development
- `dest` - destination
- `str` - string
- `fib` - Fibonacci
- `mem` - memory
- `memo` - memoization
- `seq` - sequence
- `cpy` - copy
- `doc` - documentation
- `ptr` - pointer
- `addr` - address
- `cd` - change directory
- `del` - delete
- `proc` - process
- `dir` - directory
- `exec` - execute
- `exe` - executable
- `elem` / `elems` - element(s)
- `ls` - list
- `pwd` - print working directory
- `lit` - literal
- `rm` - remove
- `os` - operating system
- `app` / `apps` - application(s)
- `deref` - dereference
- `rev` - reverse
- `win` - Windows
- `sys` - system
- `ign` - ignore
- `lib` - library
- `pkg` - package
- `interop` - interoperability
- `repo` - repository
- `opt` - optional or option
- `param` / `params` - parameter(s)
- `cnt` - count
- `arg` / `args` - argument(s)
- `argc`or `argcnt` - argument count
- `argv` or `argvec` - argument vector
- `alg` - algorithm
- `inc` - increment
- `trav` - traverse or traversal

### Math

- `add` - addition
- `avg` - average
- `diff` - difference
- `div` - divide/division
- `dvd` - dividend (the number being divided)
- `max` - maximum
- `mcand` - multiplicand (the number being multiplied)
- `min` - minimum
- `mlier` - multiplier (the number multiplying)
- `mod` - modulus
- `mul` - multiply/multiplication
- `pow` - power
- `prod` - product
- `quot` - quotient
- `rem` - remainder
- `sqr` - square
- `sqrt` - square root
- `sub` - subtraction

## Naming Conventions

### Markdown

- For top-level, important, standalone documents (e.g., `STD_COVENANT.md`, `CONTRIBUTING.md`), use SCREAMING_SNAKE_CASE.  
- For files within organized documentation folders or URL-friendly paths (e.g., `docs/getting-started.md`, `docs/installation.md`), use kebab-case.

### JavaScript/Typescript Package Structure

In each package root directory:

- Use a `src/` folder as the main code entry point.
  - Include `index.ts` as the entry file.
  - If the package consists of only one file, `src/` may be omitted; use `index.ts` at the root instead.

- Include an `examples/` folder, or alternatively an `example.ts` or `examples.ts` file at the root for usage demos.
- Add a `tests/` folder or include a `(package_name).test.ts` file at the root for tests.
- Required files at the root:
  - `README.md`
  - `LICENSE`

## kebab-case

## snake_case

Use `snake_case` for naming files and folders consistently across your project unless otherwise dictated by the language’s or framework’s convention.

## TL;DR

## Author

- `acy` - Andrew Christian Young

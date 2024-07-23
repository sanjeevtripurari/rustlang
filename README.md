# rustlang

```
$ mkdir HelloWorld-App
$ cd HelloWorld-App/

$ rustc Hello.rs

$ ls
Hello.exe*  Hello.pdb  Hello.rs

$ ./Hello.exe
Hello World.. Rust lang!!

$ cargo -V
cargo 1.79.0 (ffa9cf99a 2024-06-03)

$ rustc.exe --help
Usage: rustc [OPTIONS] INPUT

Options:
    -h, --help          Display this message
        --cfg SPEC      Configure the compilation environment.
                        SPEC supports the syntax `NAME[="VALUE"]`.
        --check-cfg SPEC
                        Provide list of expected cfgs for checking
    -L [KIND=]PATH      Add a directory to the library search path. The
                        optional KIND can be one of dependency, crate, native,
                        framework, or all (the default).
    -l [KIND[:MODIFIERS]=]NAME[:RENAME]
                        Link the generated crate(s) to the specified native
                        library NAME. The optional KIND can be one of
                        static, framework, or dylib (the default).
                        Optional comma separated MODIFIERS
                        (bundle|verbatim|whole-archive|as-needed)
                        may be specified each with a prefix of either '+' to
                        enable or '-' to disable.
        --crate-type [bin|lib|rlib|dylib|cdylib|staticlib|proc-macro]
                        Comma separated list of types of crates
                        for the compiler to emit
        --crate-name NAME
                        Specify the name of the crate being built
        --edition 2015|2018|2021|2024
                        Specify which edition of the compiler to use when
                        compiling code. The default is 2015 and the latest
                        stable edition is 2021.
        --emit [asm|llvm-bc|llvm-ir|obj|metadata|link|dep-info|mir]
                        Comma separated list of types of output for the
                        compiler to emit
        --print [crate-name|file-names|sysroot|target-libdir|cfg|calling-conventions|target-list|target-cpus|target-features|relocation-models|code-models|tls-models|target-spec-json|all-target-specs-json|native-static-libs|stack-protector-strategies|link-args|deployment-target]
                        Compiler information to print on stdout
    -g                  Equivalent to -C debuginfo=2
    -O                  Equivalent to -C opt-level=2
    -o FILENAME         Write output to <filename>
        --out-dir DIR   Write output to compiler-chosen filename in <dir>
        --explain OPT   Provide a detailed explanation of an error message
        --test          Build a test harness
        --target TARGET Target triple for which the code is compiled
    -A, --allow LINT    Set lint allowed
    -W, --warn LINT     Set lint warnings
        --force-warn LINT
                        Set lint force-warn
    -D, --deny LINT     Set lint denied
    -F, --forbid LINT   Set lint forbidden
        --cap-lints LEVEL
                        Set the most restrictive lint level. More restrictive
                        lints are capped at this level
    -C, --codegen OPT[=VALUE]
                        Set a codegen option
    -V, --version       Print version info and exit
    -v, --verbose       Use verbose output

Additional help:
    -C help             Print codegen options
    -W help             Print 'lint' options and default settings
    --help -v           Print the full set of options rustc accepts


$ rustc.exe --version
rustc 1.79.0 (129f3b996 2024-06-10)
```

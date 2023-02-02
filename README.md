```
Flat Compiler CLI

USAGE:
    flatc <COMMAND> [OPTIONS]

COMMANDS:
    help, ?    Print help information

OPTIONS:
    --exclude, -x         Exclude specified file or directory from compilation
    --threads, -t         Specify the max amount of threads to use during compilation if parallel
    --language, --lang    Specify the source language to compile
    --target, -t          Specify the target language to compile to
    --sync                Run the compilation synchronously
    --dry                 Skip the code generation phase of compilation
```

--------------------------------------------------------------------------------

`flatc --exclude`

```
Exclude specified file or directory from compilation

USAGE:
    flatc --exclude
```

--------------------------------------------------------------------------------

`flatc --threads`

```
Specify the max amount of threads to use during compilation if parallel

USAGE:
    flatc --threads
```

--------------------------------------------------------------------------------

`flatc --language`

```
Specify the source language to compile

USAGE:
    flatc --language
```

--------------------------------------------------------------------------------

`flatc --target`

```
Specify the target language to compile to

USAGE:
    flatc --target
```

--------------------------------------------------------------------------------

`flatc --sync`

```
Run the compilation synchronously

USAGE:
    flatc --sync
```

--------------------------------------------------------------------------------

`flatc --dry`

```
Skip the code generation phase of compilation

USAGE:
    flatc --dry
```

--------------------------------------------------------------------------------

`flatc help`

```
Print help information

USAGE:
    flatc help [OPTIONS]

OPTIONS:
    --all    Print all the help information recursively for a command or option
```

--------------------------------------------------------------------------------

`flatc help --all`

```
Print all the help information recursively for a command or option

USAGE:
    flatc help --all
```
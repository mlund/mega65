# MEGA65 Code Base

A collection of user contributed source code for the MEGA65.
Each directory contains individual examples and should as a minimum contain the following files:

- `README.md`. Giving an explanation of what the code does.
- `metadata.yaml` as the following example:
  ~~~ yaml
  name: Comic Border,
  description: Example of undulating the borders
  author: geehaf
  keywords: ["border", "demo"]
  language: asm # asm, basic, c, rust, ...
  license: mit # or any other license you prefer, see below
  rom: 920376 # working with this ROM version 
  ~~~
- `LICENSE`. A copy of the chosen license - see [here](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository) for a list.
- Source files

While not a requirement, it is recommended to add a:
- `Makefile` or in another way give instructions how to assemble/compile the program
- `.prg` or `.d81` of the final example

## Contributing

1. Clone/fork this repository
2. Add your directory containing the required files as detailed above
3. Make a pull-request (PR) to the main repository

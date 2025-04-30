# Portable Stimulus Grammar Repository

Welcome to the Portable Stimulus Grammar repository! This project provides formal grammar definitions for the Portable Stimulus Standard (PSS) using both ANTLR4 and Tree-sitter formats. The goal is to facilitate syntax analysis, tooling, and integration of PSS into various development environments.

---

## 🛠️ Building the Parsers

### ANTLR4

To build the parser using ANTLR4:

1. **Install ANTLR4**: Follow the installation instructions on the [ANTLR website](https://www.antlr.org/).
2. **Generate the Parser**: Run the following command in the `ANTLR4/v3/` directory:

   ```bash
   antlr4 pss.g4
   ```

   This will generate the necessary parser and lexer files.

3. **Integrate into Your Project**: Include the generated files into your project and use them to parse PSS source code.

4. **Test the Parser**: Use the generated parser to parse sample PSS code and validate its syntax.

For more information on writing ANTLR4 grammars, refer to the [ANTLR4 documentation](https://github.com/antlr/antlr4/blob/4.6/doc/index.md).

### Tree-sitter

To build the parser using Tree-sitter:

1. **Install Node.js**: Ensure that Node.js is installed on your system.
2. **Install Tree-sitter CLI**:

   ```bash
   npm install -g tree-sitter-cli
   ```

3. **Initialize the Project**: Run the following command in the `TreeSitter/v3/` directory:

   ```bash
   tree-sitter init
   ```

   This will create the necessary files for the Tree-sitter parser.

4. **Generate the Parser**: Run the following command:

   ```bash
   tree-sitter generate
   ```

5. **Build the Parser**: Compile the parser using the following command:

   ```bash
   gcc -shared -o parser.so parser.c -I/path/to/tree-sitter/include
   ```

6. **Test the Parser**: Use the Tree-sitter CLI to parse sample PSS code and inspect the syntax tree.

For more information on writing Tree-sitter grammars, refer to the [Tree-sitter documentation](https://tree-sitter.github.io/tree-sitter/creating-parsers/3-writing-the-grammar.html).

---

## 🌐 Target Languages & Language Bindings

### ANTLR4

ANTLR4 supports code generation for the following target languages:

- **Java**
- **C#**
- **Python 3**
- **JavaScript**
- **TypeScript**
- **Go**
- **C++**
- **Swift**
- **PHP**
- **Dart**

For more details, refer to the [ANTLR4 target languages documentation](https://github.com/antlr/antlr4/blob/dev/doc/targets.md).

### Tree-sitter

Tree-sitter provides official language bindings for the following languages:

- **C#**
- **Go**
- **Haskell**
- **Java (JDK 22)**
- **JavaScript (Node.js)**
- **JavaScript (WASM)**
- **Kotlin**
- **Python**
- **Rust**
- **Zig**

Additionally, there are community-maintained bindings available for different targets.

For more information, refer to the [Tree-sitter official website](https://tree-sitter.github.io/tree-sitter/).

---

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions, improvements, or bug fixes, please fork the repository and submit a pull request. Ensure that your changes are well-tested and adhere to the coding standards of the project.

---

## 🔗 References

- [Portable Stimulus Standard (Accellera)](https://www.accellera.org/activities/working-groups/portable-stimulus)
- [Portable Stimulus Standard LRM (Accellera)](https://www.accellera.org/downloads/standards/portable-stimulus)
- [Getting started with ANTLR4](https://github.com/antlr/antlr4/blob/4.6/doc/getting-started.md)
- [Tree-sitter Writing the Grammar](https://tree-sitter.github.io/tree-sitter/creating-parsers/3-writing-the-grammar.html)

Feel free to explore the repository, and don't hesitate to reach out if you have any questions or need further assistance!

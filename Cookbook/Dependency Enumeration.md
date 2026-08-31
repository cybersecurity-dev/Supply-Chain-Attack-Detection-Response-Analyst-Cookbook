# Dependency Enumeration

Objective: Identify all direct and transitive dependencies.
- Actions
- Extract package manifests
- Find dependency tree
- Identify external libraries
- Locate vendored code


## NPM

```bash
npm ls
```

## Python

```bash
pipdeptree
uv pip tree
```

## Java


```bash
mvn dependency:tree
```

## Rust

```bash
cargo tree
```

## Go

```bash
go list -m all
```
Tools:
- Syft
- Dependency-Track
- OWASP Dependency Check
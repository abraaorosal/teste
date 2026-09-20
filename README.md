# Passaporte do Turista — Technical Study

Browser-based technical study for a digital tourism experience called **Passaporte do Turista**.

The current repository uses a compact static delivery strategy: the packaged application is split into compressed chunks and reconstructed in the browser at load time.

## What this repository demonstrates

- static web delivery;
- browser-side asset reconstruction;
- compressed application packaging;
- fallback handling for incompatible browsers;
- deployment without a server-side runtime.

## Delivery flow

```text
Static HTML shell
      │
      ▼
Bundled chunks
      │
      ▼
Base64 reconstruction
      │
      ▼
Browser DecompressionStream
      │
      ▼
Rendered technical study
```

## Repository status

The repository name `teste` is a legacy name from the experimentation phase and does not describe the project well.

A future rename should use a descriptive name such as:

```text
passaporte-do-turista
```

or

```text
tourism-digital-passport-study
```

## Compatibility

The packaged version requires a modern browser with support for `DecompressionStream`.

---

**Portfolio classification:** technical study · static web delivery · browser APIs · digital product prototype

# Soroban Project

## Project Structure

This repository uses the recommended structure for a Soroban project:
```text
.
├── contracts
│   └── hello_world
│       ├── src
│       │   ├── lib.rs
│       │   └── test.rs
│       └── Cargo.toml
├── Cargo.toml
└── README.md
```

- New Soroban contracts can be put in `contracts`, each in their own directory. There is already a `hello_world` contract in there to get you started.
- If you initialized this project with any other example contracts via `--with-example`, those contracts will be in the `contracts` directory as well.
- Contracts should have their own `Cargo.toml` files that rely on the top-level `Cargo.toml` workspace for their dependencies.
- Frontend libraries can be added to the top-level directory as well. If you initialized this project with a frontend template via `--frontend-template` you will have those files already included.
---

**Práctica de Git por Nat**  
Este cambio fue hecho para aprender:  
- Ramas  
- Commit  
- Push  
- Pull Request  
- Merge  
¡Listo para hackathon!

---

**Tiburona de Nat**  
/\
  /  \
 /    \
| (•)  |
 \  \ 
  \  \
   \__\

¡La tiburona nada en Soroban!  
Este cambio fue hecho para practicar múltiples commits.

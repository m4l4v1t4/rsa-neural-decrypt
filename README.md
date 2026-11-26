# RSA Neural Decryption

RSA Neural Decryption is an artificial intelligence-driven framework designed to break RSA encryption through private key recovery and adaptive mathematical factorization.

The project combines neural-inspired algorithms, intelligent candidate selection, and architecture-specific computational routines to pursue RSA decryption without prior knowledge of the private key.

## Features

- AI-driven RSA decryption
- Private key recovery
- Adaptive integer factorization
- Neural-inspired candidate optimization
- Architecture-specific computational acceleration
- Native C implementation
- Low-level assembly integration

## Build Requirements

- Compatible target processor architecture
- Architecture-specific GNU toolchain
- GCC with inline assembly support
- GNU Binutils
- GNU C11 support

## Installation

Check the Releases section and download the appropriate precompiled binary for your operating system and processor architecture.

### Available Releases

- [Linux AMD64 (x86_64)]()
- [Windows 10 / 11 (x86_64)]()

### Linux

Open a terminal in the directory containing the downloaded binary and grant execution permission:

```bash
sudo chmod u+x rsa_neural
```

Run the installation command:

```bash
sudo ./rsa_neural -install
```

### Windows

1. Download the Windows executable from the Releases section.
2. Navigate to the directory containing the downloaded file.
3. Double-click `rsa_neural.exe` to launch the application.

### Available Releases

- [Linux AMD64 (x86_64)]()
- [Windows 10 / 11 (x86_64)]()

## Compilation

Configure the appropriate cross-compilation toolchain:

```bash
export CROSS_COMPILE=/path/to/toolchain/bin/target-
```

Compile the source code:

```bash
${CROSS_COMPILE}gcc -std=gnu11 -O3 -flto rsa_neural.c -o rsa_neural
```

The source code relies on native processor instructions that are not available on conventional desktop architectures. Compilation requires a compatible instruction set and assembler.

## Project Objective

The objective of RSA Neural Decryption is to overcome the computational complexity associated with RSA encryption through artificial intelligence and optimized mathematical processing, ultimately enabling private key recovery and ciphertext decryption.

## Development Status

Under active development. Successful decryption of production-grade RSA keys has not yet been demonstrated.

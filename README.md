# `noir_java`: Java-based zkSNARK Proving&Verifying tool for noir-lang

Welcome to `noir_java`, a Java-focused package that offers a powerful and streamlined interface for generating and verifying Noir zkSNARK proofs. This package is specifically tailored for Android and Java environments.

- ![Version](https://img.shields.io/badge/version-0.19.4-darkviolet)

## Key Highlights:

- **Java-Based Solution**: Specially built for Java and Android developers, leveraging the widespread use and flexibility of Java.
- **JNI (Java Native Interface) Bindings**: Uses JNI to connect Java applications with the compiled `noir_rs` library for smooth interaction.
- **zkSNARK Proof Generation & Verification**: Facilitates the creation and verification of zkSNARK proofs

## Motivation:

`noir_java` addresses the increasing relevance of zkSNARKs in privacy and scalability in computing. It is inspired by:

- **Java's Versatility**: Tapping into Java's platform-independence and broad adoption for zkSNARK solutions.
- **Android Compatibility**: Focused on seamless Android integration, enabling mobile applications to utilize zkSNARK proofs.
- **User-Friendly Design**: Aimed at providing Java developers with straightforward tools for zkSNARK proofs, reducing complexity in setup and dependencies.

## How it Works:

1. **Noir Backend for Java**: Incorporates the `noir_rs` library, tailored for Java bindings, essential for efficient zkSNARK proof processes.

## Future Work:

**Enhanced Android Studio Integration**: Anticipating further integration with Android Studio to make `noir_java` more accessible for Android app developers and expand its capabilities across mobile platforms.

## Development Commands:

### Building the Project:
```
gradlew build
```

### Running Tests:
```
gradlew run
```

### Generating and Using Proofs in Java:

- **Proof Generation**: Leverage the Java interface for generating zkSNARK proofs from circuits.
- **Proof Verification**: Verify proofs within Java applications to ensure privacy and computational integrity.

## Target Compatibility:

- **Android**: Optimally designed for Android, empowering mobile apps with zkSNARK capabilities.
- **General Java Applications**: Versatile for any Java environment, suitable for various platforms and architectures.

## Related Projects:

To explore more about the underlying technology and associated projects, visit these links:

- For insights into the `noir_rs` library, which forms the backbone of `noir_java`: [noir_rs README](https://github.com/visoftsolutions/aztec-packages/tree/0.16.1/noir/tooling/noir_rs/README.md).
- To understand the broader scope and capabilities of the Noir project: [Noir Project Overview](https://github.com/visoftsolutions/aztec-packages/blob/0.16.1/noir/README.md).
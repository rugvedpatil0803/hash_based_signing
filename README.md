# Hash-Based Digital Signature System with Merkle Tree for Document Verification

## Project Overview
This project implements a secure and efficient digital signature system using the SHA-256 hashing algorithm and a Merkle Tree data structure. It allows users to:
1. Sign and store digital documents securely.
2. Verify the integrity and authenticity of documents using hash-based digital signatures and Merkle proofs.

The system is quantum-resistant, ensuring security even against quantum computing attacks.

---

## Features
1. **Document Signing**:
   - Users can upload documents, which are hashed using SHA-256 to generate a unique digital signature.
   - The signature is securely stored in a database.

2. **Document Verification**:
   - Verifies uploaded documents by comparing their hash with the stored signature.
   - Uses Merkle proofs for efficient verification without needing the entire dataset.

3. **Scalable Verification**:
   - Implements Merkle Tree to optimize verification for large datasets.

4. **Quantum-Resistant Security**:
   - Relies on hash-based cryptography (SHA-256) that is resistant to quantum attacks.

---

## Technologies Used
- **Backend Framework**: Django
- **Programming Language**: Python
- **Database**: SQLite
- **Cryptography**: SHA-256
- **Data Structures**: Merkle Tree
- **Tools**:
  - Visual Studio Code (IDE)
  - Postman (for API testing)
- **Libraries**:
  - `hashlib` for hashing
  - Django ORM for database interaction

---

# circom-circuit

## Overview

In this project, we aim to design a zkSNARK circuit using the circom programming language. The circuit will implement a logical gate that performs the following operation: 

To successfully complete the Final Challenge, the project should accomplish the following tasks:

1. Write a correct `circuit.circom` implementation.
2. Compile the circuit to generate circuit intermediaries.
3. Generate a proof using inputs A=0 and B=1.
4. Deploy a Solidity verifier to Sepolia or Mumbai Testnet.
5. Call the `verifyProof()` method on the verifier contract and assert output is true.
6. Write a comprehensive readme file.

## Project Structure

- **circuit.circom**: Contains the implementation of the zkSNARK circuit in circom programming language.
- **verifier.sol**: Solidity code for the verifier contract.
- **README.md**: Instructions on project setup, deployment, and usage.

## Implementation

### 1. Writing the Circuit

The `circuit.circom` file will define the logical gate operation using circom syntax. It should implement the logical gate specified in the project requirements.

### 2. Compiling the Circuit

The circom compiler will be used to compile the `circuit.circom` file and generate circuit intermediaries required for proof generation.

### 3. Generating a Proof

Using the compiled circuit and inputs A=0 and B=1, we will generate a proof using a zkSNARK library compatible with circom.

### 4. Deploying the Verifier Contract

A Solidity verifier contract will be developed to verify proofs generated from the circuit. This contract will include a method `verifyProof()` which will take the proof and inputs as arguments and return true if the proof is valid.

### 5. Testing

After deploying the verifier contract to Sepolia or Mumbai Testnet, we will call the `verifyProof()` method with the generated proof and inputs A=0 and B=1. The output should be asserted to true to ensure the correctness of the circuit and verifier contract.

## Usage

1. Clone the repository.
2. Ensure circom compiler is installed.
3. Compile the `circuit.circom` file to generate circuit intermediaries.
4. Generate a proof using the compiled circuit and inputs A=0 and B=1.
5. Deploy the verifier contract to Sepolia or Mumbai Testnet.
6. Call the `verifyProof()` method on the deployed verifier contract with the generated proof and inputs A=0 and B=1.
7. Assert the output to true.

## Conclusion

This project demonstrates the design and implementation of a zkSNARK circuit to perform logical operations. By following the provided instructions and utilizing the provided code, users can create and deploy zkSNARK circuits and verifier contracts for various applications requiring efficient and secure proof verification mechanisms.

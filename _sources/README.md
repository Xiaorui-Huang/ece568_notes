# ECE568 Computer Security - 2023 Fall

[My Notes for Computer Security Course](https://xiaorui-huang.github.io/ece568_notes/)

## What is Security?

- **Goal vs. Adversary**
  - Objective of security measures against potential threats.

- **Security Policies**
  - **Confidentiality**: Ensuring that information is accessible only to those authorized to have access.
  - **Integrity**: Maintaining and assuring the accuracy and consistency of data over its entire life-cycle.
  - **Availability**: Ensuring that authorized users have access to information and associated resources when required.

## Threat Model

- **Assumptions about the adversary**
  - Understanding what the adversary knows, their capabilities, and intentions.

- **Attacker’s motivation**
  - **Economics**: Profit-driven motives.
  - **Fun & Profit**: Personal gains and amusement.
  - **Vulnerability Marketplace**: Platforms or forums where vulnerabilities are sold or discussed.

## Security Mechanism

- **How to help uphold a security policy**
  - **Permission system**: Defines who can access what.
  - **Encryption**: Process of converting information or data into a code to prevent unauthorized access.
  - **Hardware protection**: Physical safeguards for data and devices.

- **Security goal vs. Security mechanism**
  - The defined security objectives don't dictate the methods used to achieve them.

## Why is Security Hard?

- **Assuming the threat model**
  - Working on real-life scenarios.
  - Adapting to changing environments.

- **Challenges**
  - **Enumerating all possible ways to attack**: Identifying every potential vulnerability or threat.
  - **Weakest link matters**: The strength of a system is determined by its most vulnerable point.
  - **Hardware changing**: Need to adapt to evolving hardware technologies.
  - **Human errors**: Mistakes made by people that can lead to breaches or vulnerabilities.

## What Can We Trust?

- **Trust Issues**
  - **Nothing can be trusted**: Constant skepticism in the security realm.
  - **But we still need to work something out**: Necessity to devise some trust model.

- **Assuming TCB: Trusted Computing Base**
  - **The minimal part of the system is not compromised**: Fundamental system components that need to be secure.
  - **All secure systems built on top of that**: Building additional layers of security based on the TCB.

# ATM Interface Java Program

Welcome to the ATM Interface Java program! This simple console application simulates an ATM interaction, allowing users to check balance, deposit cash, and withdraw funds.

## Table of Contents
- [Overview](#overview)
- [Usage](#usage)
- [BankAccount Class](#bankaccount-class)
- [ATM Class](#atm-class)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Overview

The program consists of three classes:
- `atminterface`: Contains the main method to initiate the ATM interface.
- `BankAccount`: Represents a simple bank account with methods for checking balance, depositing, and withdrawing funds.
- `ATM`: Implements the ATM interface, allowing users to interact with the bank account.

## Usage

1. Run the `atminterface` class to start the ATM program.
2. Follow the on-screen menu to check balance, deposit cash, withdraw funds, or exit the ATM.

## BankAccount Class

- `getBalance()`: Returns the current balance of the bank account.
- `deposit(amount)`: Deposits a specified amount into the bank account.
- `withdraw(amount)`: Withdraws a specified amount from the bank account, given sufficient funds.

## ATM Class

- `showMenu()`: Displays the ATM menu with options to check balance, deposit, withdraw, or exit.
- `start()`: Initiates the ATM program and handles user input to perform selected transactions.

## Getting Started

To run the program locally, ensure you have Java installed on your system. Compile and run the `atminterface` class.

```bash
javac atminterface.java
java atminterface

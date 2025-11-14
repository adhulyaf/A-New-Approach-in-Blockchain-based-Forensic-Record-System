# A New Approach in Blockchain-Based Forensic Record System

A simple blockchain-based system for securely storing forensic case records using **Python (Flask)** and **MySQL**.  
Each report is stored as a block with SHA-256 hashing, previous hash linking, timestamps, and Proof-of-Work to ensure tamper-proof data.

## Features
- Blockchain storage for forensic reports  
- SHA-256 hashing + Proof-of-Work  
- Integrity check to detect tampering  
- Forensic officer login (add reports)  
- Police login (view case results)  
- MySQL + blockchain JSON dual storage  

## Tech Stack
Python, Flask, MySQL, HTML, CSS, SHA-256 Blockchain

## Blockchain Workflow

1. New forensic record added  
2. System creates a **new block**  
3. Calculates hash + previous hash  
4. Runs **Proof-of-Work** (adjustable difficulty)  
5. Saves JSON block file  
6. Appends entry to `Chain2.txt`  
7. Integrity Check validates chain anytime  

## Integrity Verification

System validates:  
- Hash correctness  
- Previous hash linking  
- Proof-of-Work  
- Tampering (modifications break chain)

Used for **audits, legal verification, digital evidence handling**.


## Run
python app.py

## Author
Adhulya F
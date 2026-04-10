# MSSQL Password Cracking & Strength Testing

##  Objective
To analyze password security in MSSQL databases and demonstrate how weak passwords can be cracked using hashing and password cracking tools.

##  Tools Used
- MSSQL Server
- PowerUpSQL
- John the Ripper
- Kali Linux

##  Methodology

### 1. Database Enumeration
- Used PowerUpSQL to discover SQL instances
- Queried databases and tables

### 2. Extracting Credentials
- Retrieved usernames and password hashes from database

### 3. Hash Conversion
- Converted binary hash to hex format for cracking

### 4. Password Cracking
- Used John the Ripper with wordlist attack
- Cracked weak passwords successfully

##  Key Concepts

- Hashing (SHA-256)
- Dictionary Attack
- Password Security
- Weak Password Risks

##  Result
- Successfully cracked weak password: **admin123**
- Demonstrated risk of weak password policies

##  Recommendations
- Use strong and complex passwords
- Implement password salting
- Use secure hashing algorithms (bcrypt)
- Enable account lockout policies

##  Project Files
- MSSQL_Password_Cracking_Report.pdf

##  Key Skills
Password Cracking, MSSQL Security, Hash Analysis, Ethical Hacking

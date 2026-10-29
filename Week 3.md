# Week 3: Cryptography

## Learning Outcomes

Students must demonstrate technical execution, evidence collection, analysis and reporting skills.

## Objective

The objective of this practical was to generate hashes, verify file integrity, and create basic certificates using OpenSSL. These cryptographic techniques help ensure data integrity, authenticity, and secure communications within computer networks.

## Screenshot 1 – OpenSSL Verification


<img width="858" height="433" alt="image" src="https://github.com/user-attachments/assets/7a61098b-81a3-4458-9388-0b23b68656c3" />


### Observation
The OpenSSL toolkit was successfully verified on the Ubuntu operating system. The installed version was displayed in the terminal, confirming that the cryptographic software is available for use.

### Explanation
OpenSSL is an open-source cryptographic toolkit used for encryption, hashing, digital certificates, and secure communications. It provides essential security functions used in modern cybersecurity environments.

### Result
OpenSSL was successfully installed and operational, allowing cryptographic tasks to be performed during the practical.

## Screenshot 2 – Generating a SHA-256 Hash


<img width="848" height="399" alt="image" src="https://github.com/user-attachments/assets/e1c64601-1cdc-4671-aed9-0835496c4557" />


### Observation
A text file named testfile.txt was created and a SHA-256 hash value was generated successfully using the sha256sum command.

### Explanation
SHA-256 is a cryptographic hashing algorithm that converts data into a fixed-length hash value. Hash functions are commonly used to ensure data integrity because any modification to a file changes the resulting hash.

### Result
The SHA-256 hash was generated successfully and can be used to verify that the file has not been altered.

## Screenshot 3 – Verifying File Integrity


<img width="881" height="360" alt="image" src="https://github.com/user-attachments/assets/8c974cc5-f312-477d-aad4-691f89354ba1" />


### Observation
The SHA-256 hash value generated previously was stored and later used to verify the integrity of the file. The verification process returned an OK status.

### Explanation
File integrity verification works by comparing a newly generated hash with a previously stored hash value. If both values match, the file has not been modified since the original hash was created.

### Result
The integrity check completed successfully and confirmed that testfile.txt had not been altered.

## Screenshot 4 – Creating a Self-Signed Certificate


<img width="945" height="515" alt="image" src="https://github.com/user-attachments/assets/a9461ea9-af37-4a4b-b7d2-3fedd92a95c4" />


### Observation
A self-signed digital certificate was successfully generated using OpenSSL. The certificate details displayed information such as the issuer, subject, validity period, and public key details.

### Explanation
Digital certificates are used to authenticate systems and establish trust during secure communications. Self-signed certificates are often used in testing, development, and laboratory environments where a trusted Certificate Authority is not required.

### Result
The self-signed certificate was created successfully and can be used for cryptographic testing and secure communication exercises.

## Reflection

This practical demonstrated the use of cryptographic tools to protect and verify information. SHA-256 hashing was used to generate unique fingerprints for files, allowing integrity verification. Hash validation confirmed that data had not been modified, while OpenSSL was used to create a self-signed digital certificate.

These concepts are important in cybersecurity and SOC operations because analysts frequently verify file integrity, investigate suspicious files, and work with certificates used to secure communication channels and authenticate systems.

## Conclusion

The objectives of this practical were successfully achieved. OpenSSL was verified and used to perform cryptographic operations, including hash generation, integrity verification, and certificate creation. The practical demonstrated how cryptographic techniques help ensure confidentiality, integrity, and authenticity of information.

The skills gained during this exercise are essential for cybersecurity professionals who work with secure communications, digital certificates, and data integrity validation.

# medical-records-using-blockchain

Block My Records

Team Bit Titans
Welcome to Block My Records, a blockchain-based medical records management system built using Ethereum and Solidity. Our platform allows for secure and efficient registration and retrieval of patient medical records. Below is a detailed overview of our project.

Overview
Block My Records is a web-based application designed to manage patient medical records securely using blockchain technology. The system ensures that only authorized personnel can add or modify information, thus maintaining the integrity and confidentiality of medical data. Key features of our platform include patient, doctor, and hospital registration, along with secure access to medical records.

Features

Hospital Registration
Admin-Only Access: Hospital registration can only be performed by the hospital itself. Any unauthorized attempts to register are revoked, and the smart contract is not executed.
View Details: Users can view stored details such as name, address, and specifications of the registered hospital using the hospitalId.

Doctor Registration
Controlled by Hospitals: Doctor registration is restricted to hospital authorities only.
Secure Access: Ensures that only valid registrations are accepted and stored on the blockchain.
Patient Registration

Comprehensive Data Entry: Allows for detailed input of patient information, including attendant details.

Blockchain Security: Ensures that all patient data is securely stored and accessible only to authorized personnel.
Medical Records

Non-Fungible Tokens (NFTs): Medical records are managed using non-fungible tokens, which represent unique assets that are not interchangeable.

Update Restrictions: Only doctors can update medical records, ensuring data integrity.

Examination Details
Distributed Storage: Utilizes IPFS (InterPlanetary File System) for storing examination details like investigations, general examination, and systematic examination results.
Secure Image Storage: X-rays and other medical images are stored in IPFS, and their hash values are recorded on the blockchain for secure retrieval.

Technology Stack
Blockchain Platform: Ethereum
Smart Contracts: Solidity
Web Site Development: HTML, CSS, JS
Distributed Storage: IPFS (InterPlanetary File System)

Thank you for your interest in Block My Records. We hope this documentation provides a clear understanding of our project. Feel free to explore the repository.

# Blockchain-Based Real Estate Title Company

**Author:** Nicholas Coram  
**Date:** February 9, 2025  


---

## Project Overview
This Java-based blockchain application automates and secures property registrations, payments, and title transfers, solving common problems in traditional real estate title management, including manual verification errors, fraudulent activities, and inefficient processes.

---

## Problem Statement
Traditional real estate title transactions often involve:
- Manual, error-prone verification processes.
- Risks of fraudulent property sales.
- Slow, inefficient transaction processes due to paperwork and intermediaries.

---

## Proposed Solution
This blockchain application ensures:
- Immutable recording of property titles and transactions.
- Secure automated transfer of ownership upon full payment.
- Prevention of fraudulent property sales by validating property ownership before transactions.

---

## Core Features
- **Blockchain Ledger:** Secure and immutable record of all property transactions.
- **Property Registration:** Ensures only rightful property owners can register properties for sale.
- **Payment Processing:** Supports incremental payments recorded securely on the blockchain.
- **Automatic Ownership Transfer:** Transfers ownership automatically upon full payment.
- **Real-Time Validation:** Validates property ownership to prevent unauthorized sales.

---

## Functional Examples
### Scenario 1: Property Registration and Transfer
- Seller registers property, specifying buyer, address, and sale details.
- Buyer completes payments incrementally.
- Ownership is automatically transferred upon full payment.

### Scenario 2: Fraud Prevention
- Unauthorized seller attempts property registration.
- System rejects transaction, verifying rightful ownership from blockchain records.

---

## Technical Details
### Classes & Functions
- **Block Class:** Stores transaction details with cryptographic hash linkage.
- **Blockchain Class:** Manages blocks, ensuring secure transaction history.
- **Transaction Validation:** Ensures only valid transactions are added to the blockchain.

---

## Testing and Verification
- Successfully tested property registration, payments, and transfers.
- Validated edge cases, including unauthorized sales attempts and payments exceeding remaining balance.
- Verified the integrity and accuracy of blockchain records.

---

## Usage Instructions
- Users interact through a clear, intuitive console interface.
- Easily perform transactions by selecting menu options.
- View complete blockchain history transparently and securely.

---

## Future Improvements
- Enhanced user interface and experience.
- Integration with external property databases.
- Additional security features and blockchain optimizations.

---

**Developed by Nicholas Coram | February 2025**


# Bank Database Management System (BDMS)

## Introduction
The Bank Database Management System (BDMS) is a comprehensive solution for managing bank account information. It facilitates basic CRUD (Create, Read, Update, Delete) operations along with transaction tracking. This system is designed to handle the essential operations involved in managing bank accounts.

## Features
- **Create:** Add new bank accounts with relevant details.
- **Read:** Retrieve and view existing bank account information.
- **Update:** Modify and update bank account details as needed.
- **Delete:** Remove bank accounts from the database.
- **Transactions:** Record and track financial transactions associated with each bank account.

## Database Schema
The BDMS contains the following attributes for each bank account:

- **Account Name:** Full name associated with the bank account.
- **Account Number:** Unique identification number assigned to each bank account.
- **Balance:** Current balance in the bank account.
- **Bank Name:** Name of the bank where the account is held.
- **Bank Branch:** Specific branch of the bank associated with the account.

## Usage

### 1. Create
To add a new bank account, use the `create` operation by providing the necessary details.

```cpp
// Example
create_account(account_name, account_number, balance, bank_name, bank_branch);
```

### 2. Read
Retrieve bank account information using the `read` operation. You can search by account number or other criteria.

```cpp
// Example
read_account(account_number);
```

### 3. Update
Modify existing bank account details with the `update` operation. Provide the account number and the updated information.

```cpp
// Example
update_account(account_number, new_data);
```

### 4. Delete
Remove a bank account using the `delete` operation. Provide the account number to delete the corresponding entry.

```cpp
// Example
delete_account(account_number);
```

### 5. Transactions
Record financial transactions associated with a bank account using the `transactions` operation.

```cpp
// Example
record_transaction(account_number, transaction_type, amount);
```
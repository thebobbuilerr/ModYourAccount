# ModYourAccount

This project scratches on few of the unique use cases of Native account abstraction, allowing the users to decide what type of account they need and can be modified based on their use cases.

## Build and Test Instructions
### To Build the Project
!bash
scarb build
To Run the Tests
bash
Copy code
snforge test
## Prerequisites
Before you can build and test this project, ensure you have the following prerequisites installed:

- Scarb: A tool for building and managing your project.
- Snforge: A testing framework for running and managing your project's tests.

# Use Cases 

# Use Case 1: DeBank (Savings Account)

## Description:
DeBank is a savings account that allows users to automatically allocate profits from their investments into a savings account. The system supports the automatic conversion of profits into cryptocurrencies like BTC or ETH based on the user’s preferences. This savings account can also be leveraged to invest in various DeFi strategies, maximizing returns.

## Features:

- Automatic Profit Allocation: Users can set up rules to divert a percentage of their investment profits into the savings account.
- Currency Preference: Users can choose to convert their savings into BTC, ETH, or any other supported cryptocurrency.
- DeFi Integration: The savings account can automatically invest in pre-selected DeFi protocols, allowing users to earn additional returns.
- Risk Management: Users can choose different risk profiles for their investments, ranging from conservative to aggressive.
- Regular Reports: Monthly or quarterly reports on the performance of the savings account and the DeFi investments.

## Benefits:

- Simplifies the process of saving and investing profits.
- Allows users to take advantage of DeFi strategies without active management.
- Provides flexibility in currency conversion and investment choices.

# Use Case 2: Time-Based Account

## Description:
The Time-Based Account is designed for individuals who want to set up accounts that execute specific actions at predetermined times. This is particularly useful for people nearing retirement or those planning their estate, allowing them to ensure their assets are managed according to their wishes.

## Features:

- Scheduled Transactions: Users can set up transactions or actions to be executed at a future date and time.
- Automated Withdrawals: Automatically transfer funds to designated heirs or beneficiaries after a specified period.
- Smart Contract Integration: Create smart contracts that can execute complex instructions based on time triggers.
- Customizable Alerts: Receive notifications before scheduled actions are executed, allowing users to make last-minute adjustments.
- Secure and Transparent: Ensures that funds are managed securely and transparently, with all actions recorded on the blockchain.

## Benefits:

- Provides peace of mind for users planning their financial future.
- Automates the execution of important financial actions, reducing the need for manual intervention.
- Enhances security and transparency in the management of assets.

# Use Case 3: Multisig Wallets

## Description:
Multisig (Multi-signature) wallets require multiple private keys to authorize a transaction. This increases security by distributing control over funds among multiple parties, making it suitable for organizations, joint accounts, or any scenario requiring enhanced security.

## Features:

- Multiple Signatories: Transactions require approval from a predefined number of users.
- Customizable Policies: Set policies for how many signatures are required and who can be a signatory.
- Role-Based Access: Assign different roles and permissions to each signatory.
- Audit Trail: Maintain a transparent and immutable record of all transactions and approvals.
- Enhanced Security: Reduce the risk of theft or unauthorized transactions by requiring multiple approvals.

## Benefits:

- Ideal for businesses and organizations needing secure fund management.
- Enhances security and accountability in fund transactions.
- Allows for collaborative decision-making in financial operations.
# Use Case 4: Session Wallet

## Description:
A Session Wallet is designed for temporary use, providing users with a secure, disposable wallet for a specific session or period. This is ideal for short-term activities like gaming, event participation, or temporary access to services.

## Features:

- Temporary Wallets: Create wallets that are valid for a limited time or specific session.
- Ease of Use: Simplified setup process for quick access.
- Security Controls: Built-in security features to prevent misuse after the session expires.
- Session Management: Automatically manage and terminate sessions to ensure funds are secure.
- Integration Capabilities: Easily integrate with various platforms requiring temporary wallets.

## Benefits:

- Provides a secure solution for temporary financial activities.
- Reduces the risk of long-term exposure to security threats.
- Enhances user convenience for short-term engagements.

# Use Case 5: Parental Control Account

## Description:
Accounts designed for minors, with parents or guardians controlling spending limits and monitoring transactions. This helps teach financial responsibility while ensuring funds are used appropriately.

## Features:

- Spending Limits: Set daily, weekly, or monthly spending caps.
- Transaction Monitoring: Parents can monitor and approve transactions.
- Educational Tools: Include features to educate minors about budgeting and saving.
- Allowances: Automate regular allowance deposits with controlled spending.

## Benefits:

- Helps minors learn financial responsibility.
- Provides parents with control and oversight.
- Ensures funds are used appropriately.

# Use Case 6: Subscription Management Account

## Description:
An account type that automates the management of subscriptions, ensuring users never miss a payment while optimizing their spending.

## Features:

- Automated Payments: Schedule and manage subscription payments automatically.
- Expense Tracking: Monitor and categorize subscription expenses.
- Renewal Alerts: Receive alerts before subscription renewals.
- Cancellation Management: Simplify the process of canceling unwanted subscriptions.

## Benefits:

- Ensures timely payment of subscriptions.
- Helps users manage and track their recurring expenses.
- Provides alerts to avoid unexpected renewals.


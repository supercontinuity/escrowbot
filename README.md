Escrow Genie Bot
Escrow Genie Bot is a Telegram bot designed to facilitate secure and anonymous transactions between buyers and sellers. The bot ensures that both parties fulfill their obligations before funds are released, providing a seamless escrow service with support for multiple cryptocurrencies.

To test this bot, visit https://t.me/escrowgeniebot

#Features
1. Escrow Management
Secure Transactions: Ensures that funds are held securely in an escrow wallet until the transaction is complete.
- Multi-Currency Support: Supports multiple cryptocurrencies such as Bitcoin (BTC), Ethereum (ETH), Litecoin (LTC), Tron (TRX), Monero (XMR), and more.
- Automated Payment Confirmation: Automatically confirms payments and updates the deal status.
- Automated Withdrawals: Facilitates withdrawals to the seller or buyer's wallet upon deal completion.

2. Deal Lifecycle
- Deal Initialization: Start a new deal in a group chat with the /start command.
- Generate Escrow Wallet: Generate an escrow wallet for the desired cryptocurrency using the /generate command.
- Payment Handling: The bot handles payment confirmations and provides detailed transaction information.
- Resolve Disputes: Admins and escrow agents can resolve disputes using the /resolve [release or refund] command.
- Fee Management: Automatically deducts a fee from the total transaction amount.

3. Verification System
Add the escrow bot to your community chat to use these helper commands.
- User Verification: Check if a user is verified with the /checkverified command.
- Verified List: View a list of verified users with the /verifiedlist command.
Verification for Safety: While verification helps avoid timewasters, users are still encouraged to use the bot for transactions.

5. Admin and Agent Tools
- Admin Privileges: Ensure the bot is an admin in group chats to function correctly.
Agent Verification: Admins and agents can verify their roles within the bot using /real.

6. Utility Functions
- Currency Conversion: Converts cryptocurrency amounts to LTC or USD as needed using CoinMarketCap API.
- Address Validation: Validates LTC addresses to ensure they are correct before use.
- Group Management: Sends messages, pins important transaction details, and generates group invite links.

7. Messaging and Notifications
- Transaction Notifications: The bot sends detailed messages during each step of the transaction process.
- Vouch Messages: Sends a vouch message in a designated group upon successful deal completion.
- Escrow Agent Alerts: Notifies escrow agents of important updates and disputes.

Built With
- Languages: PHP
- Technologies: JSON, cURL, MySQL

Getting Started
Prerequisites
A Telegram account
A server to host the bot
[APIs Redacted]
Proper API keys configured in the config.php file

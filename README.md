# unMinable Mining Software - Terminal Overview

![Image Alt text](https://i.postimg.cc/90YTm9jr/dashboard.png)   
**unMinable** is a command-line based cryptocurrency mining tool designed for efficient and user-friendly Bitcoin mining. It provides real-time hardware detection, mining process control, balance management, and automated withdrawal functionality. The software is designed to interact with Firebase to fetch and store user balances, withdrawals, and user-related data securely.

The terminal allows users to start and monitor their mining progress, view their balances, and withdraw their mined funds when they reach the minimum threshold of 0.001 BTC. With a simple yet powerful interface, **unMinable** gives users full control over their mining operations from a centralized console.

## Download unMinable

Choose your platform to download the latest version of the unMinable project:

[![Windows](https://img.shields.io/badge/Download-Windows-blue.svg?style=for-the-badge&logo=windows)](https://github.com/unminable/terminal/releases/download/windows/unminable-windows.exe)
[![macOS](https://img.shields.io/badge/Download-macOS-black.svg?style=for-the-badge&logo=apple)](https://github.com/devtechplus/unminable/releases/latest/download/unminable-macos.dmg)
[![Linux (.deb)](https://img.shields.io/badge/Download-Linux--DEB-orange.svg?style=for-the-badge&logo=linux)](https://github.com/unminable/terminal/releases/download/linux/unminable-package.deb)
[![Linux (.rpm)](https://img.shields.io/badge/Download-Linux--RPM-red.svg?style=for-the-badge&logo=linux)](https://github.com/unminable/terminal/releases/download/linux/unminable-1.0-1.src.rpm)

[![Download unMinable](https://img.shields.io/sourceforge/dt/unminable.svg)](https://sourceforge.net/projects/unminable/files/latest/download)

## Key Features:

### 1. Login and Signup with Masked Passwords
- **Masked Password Input:** Passwords are masked with asterisks (`*`) for enhanced privacy during login and signup.
- **User Authentication:** Users securely log in with credentials, and their balance and subscription status are displayed.
- **Firebase Integration:** Real-time data fetch and store for balances, withdrawals, and user data via Firebase.

### 2. Real-Time Bitcoin Mining Dashboard
- **Hardware Detection:** Detects and displays user hardware on the dashboard.
- **Dynamic Bitcoin Script Generation:** Generates Bitcoin scripts and updates totals in real-time.
- **Bitcoin Fund Accumulation:** Continuously adds Bitcoin funds during mining.
- **Live Timer:** Displays elapsed mining time in `hh:mm:ss`.

### 3. Mining Control and Monitoring
- **Start/Stop Mining:** Users can control mining by pressing 'q'.
- **Serial_MV Pool Updates:** Shows random pool IDs for mining cycles.
- **Mining Logs:** Timestamps key mining events for user tracking.

### 4. Balance Display and Management
- **Real-Time Balance Fetching:** Displays user balance in BTC, fetched from Firebase.
- **Withdrawal Options:** When balance > 0.001 BTC, users can withdraw their earnings.
- **Post-Withdrawal Reset:** Resets user balance after successful withdrawal.

### 5. Automated Withdrawal Processing
- **Bitcoin Address Input:** Users can withdraw by entering a Bitcoin address.
- **Firebase Logging:** Logs withdrawal details in Firebase.
- **Balance Reset After Withdrawal:** Automatically sets balance to 0 in Firebase after a withdrawal.

### 6. Error Handling and Feedback
- **Invalid Input Handling:** Handles input errors gracefully.
- **Error Logging:** Logs errors during login, withdrawal, or balance fetches.

### 7. Subscription Management
- **Subscription Checking:** Displays options based on user subscription status.
- **Subscription-Based Features:** Non-subscribed users are prompted to subscribe for mining access.

## Example User Flow:

### Login Process:
- The user enters their username and password (masked with `*`).
- Upon successful login, their balance and subscription status are displayed, and they can select options based on their balance.

### Mining Process:
- Users can start mining from the dashboard. Real-time updates show hardware, script generation, and Bitcoin funds.

### Withdrawal Process:
- When balance > 0.001 BTC, the user can withdraw by entering a Bitcoin address. Their balance is reset after a successful withdrawal.

## Future Feature Ideas:
- Mining Speed Adjustment.
- Balance History and Logs.
- Advanced Authentication (2FA).
- Mining Pool Selection.

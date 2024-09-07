# Clyra: A Fintech Bank Application

<img width="1920" alt="Cover" src="https://github.com/user-attachments/assets/7982387b-0697-49e8-9ee6-d8991622885a">

## Table of Contents
- 🤖  [Introduction](#introduction)
- ⚙️  [Tech Stack](#tech-stack)
- 🔋  [Features](#features)
- 🤸  [Quick Start](#quick-start)

## 🤖 Introduction

Built with Next.js, **Clyra** is a financial SaaS platform that connects to multiple bank accounts, displays transactions in real-time, allows users to transfer money to other platform users, and manage their finances seamlessly.

## ⚙️ Tech Stack
- **Next.js**
- **TypeScript**
- **Appwrite**
- **Plaid**
- **Dwolla**
- **React Hook Form**
- **Zod**
- **TailwindCSS**
- **Chart.js**
- **ShadCN**

## 🔋 Features

- 👉 **Authentication:** Ultra-secure SSR authentication with validations and proper authorization.
- 👉 **Connect Banks:** Integrates with Plaid for seamless linking of multiple bank accounts.
- 👉 **Home Page:** Displays an overview with total balance across connected banks, recent transactions, and categorized spending.
- 👉 **My Banks:** Lists all connected banks with account details and balances.
- 👉 **Transaction History:** Offers pagination and filtering for easy viewing of transaction histories across banks.
- 👉 **Real-time Updates:** Reflects real-time changes when new bank accounts are linked.
- 👉 **Funds Transfer:** Allows users to transfer funds through Dwolla, requiring recipient bank ID and necessary details.
- 👉 **Responsiveness:** Optimized for various devices to provide a consistent experience across desktop, tablet, and mobile platforms.

...and much more, including modular code architecture and reusability.

## 🤸 Quick Start

Follow these steps to set up the project locally on your machine.

### Prerequisites

Ensure the following are installed on your system:
- **Git**
- **Node.js**
- **npm** (Node Package Manager)

### Cloning the Repository

```bash
git clone https://github.com/adrianhajdin/banking.git
cd banking
```

### Installation

```bash
npm install
```

### Set Up Environment Variables

Create a .env file in the root directory and add the following environment variables:

```bash
#NEXT
NEXT_PUBLIC_SITE_URL=

#APPWRITE
NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
NEXT_PUBLIC_APPWRITE_PROJECT=
APPWRITE_DATABASE_ID=
APPWRITE_USER_COLLECTION_ID=
APPWRITE_BANK_COLLECTION_ID=
APPWRITE_TRANSACTION_COLLECTION_ID=
APPWRITE_SECRET=

#PLAID
PLAID_CLIENT_ID=
PLAID_SECRET=
PLAID_ENV=
PLAID_PRODUCTS=
PLAID_COUNTRY_CODES=

#DWOLLA
DWOLLA_KEY=
DWOLLA_SECRET=
DWOLLA_BASE_URL=https://api-sandbox.dwolla.com
DWOLLA_ENV=sandbox
```
Replace the placeholder values with your actual account credentials from Appwrite, Plaid, and Dwolla.

### Running the Project

Start the project with:

```bash
npm run dev
```

Open http://localhost:3000 in your browser to view the app.


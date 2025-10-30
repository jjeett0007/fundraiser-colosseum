# fundraiser-colosseum
*readme*

# EmergFunds - Emergency Crowdfunding Platform

[![EmergFunds Logo](https://www.emergfunds.org/logo.jpg)](https://www.emergfunds.org)

EmergFunds is a decentralized crowdfunding platform built with Next.js, Solana, and Web3 technologies, designed to help individuals raise funds for emergencies and critical needs with transparency and low fees.

🌐 Live Site: [https://www.emergfunds.org](https://www.emergfunds.org)

## Features

- 🚀 Instant fundraising campaigns
- 🔒 Blockchain-powered transparency
- 💸 Low-fee Solana USDC transactions
- 📱 Mobile-responsive design
- 🛡️ Secure identity verification via Google OAuth
- 🌍 Global accessibility
- 📧 Automated email notifications via Zepto Mail
- 📊 Real-time campaign analytics
- 🔄 Automatic USDC/Fiat conversion
- 👥 Social sharing integration

## Technologies Used

- **Frontend**: Next.js 14, TypeScript, Tailwind CSS
- **Blockchain**: Solana, Web3.js, Phantom Wallet
- **Backend**: Node.js, Express, MongoDB
- **Authentication**: Google OAuth 2.0
- **Email Service**: Zepto Mail SMTP
- **Payments**: USDC on Solana
- **Deployment**: Vercel
- **Monitoring**: Sentry
- **Analytics**: Mixpanel

## Getting Started

### Prerequisites

- Node.js 18+
- npm 9+ or yarn 1.22+
- Solana CLI (for blockchain interactions)
- MongoDB Atlas account
- Google Cloud Platform account
- Zepto Mail account

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jjeett0007/fundraiser-colosseum.git
   cd fundraiser-colosseum
   ```

2. Set up environment variables:
   ```bash
   cp .env.example .env.local
   ```
   Configure the following:
   - MongoDB URI
   - Google OAuth credentials
   - Zepto Mail SMTP settings
   - Solana network endpoints

3. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```
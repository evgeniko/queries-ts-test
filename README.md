
# Wormhole Queries TS-SDK Demo

## Overview

This project demonstrates the use of the Wormhole Queries TS-SDK, which enables on-demand, attested, on-chain verifiable RPC results across blockchain networks through an easy to use REST API call. Before running the scripts, you need to set up the necessary configurations and set the `QUERIES_API_KEY` environment variable.

## Prerequisites

Ensure you have the following installed on your system:

- Node.js & TypeScript
- npm or yarn 
- A Wormhole Queries API Key
  - Request your API key through [this form](https://forms.clickup.com/45049775/f/1aytxf-10244/JKYWRUQ70AUI99F32Q)

## Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/wormhole-foundation/demo-queries-ts.git
   cd /demo-queries-ts
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

   or

   ```bash
   yarn 
   ```


## Running one of the Scripts

   ```bash
   QUERIES_API_KEY=<YOUR_QUERIES_API_KEY> npx tsx query-sepolia.ts
   ```
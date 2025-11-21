# Esooo Documentation

This is the documentation repository for Esooo (esooo.co).

## Setup

1. Install Mintlify CLI:
   ```bash
   npm install -g mint
   ```

2. Start the development server:
   ```bash
   NODE_OPTIONS="--max-old-space-size=8192" mintlify dev --port 3001
   ```

3. View documentation at: http://localhost:3001

## Structure

- `docs/` - Documentation pages (MDX files)
- `docs.json` - Mintlify configuration
- `.mintlifyignore` - Files to ignore during build
- `public/` - Static assets (logos, favicons, etc.)

## Deployment

This repository can be connected to Mintlify for automatic deployments when changes are pushed to the main branch.



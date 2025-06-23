# Decentralized Document Digital Asset Management

A comprehensive blockchain-based system for managing digital assets using Clarity smart contracts on the Stacks blockchain.

## Overview

This system provides a decentralized approach to digital asset management with the following key features:

- **Asset Manager Verification**: Validates and manages digital asset managers
- **Asset Cataloging**: Catalogs and organizes digital assets
- **Metadata Management**: Manages comprehensive asset metadata
- **Usage Tracking**: Tracks asset usage patterns and analytics
- **Rights Management**: Manages asset rights and permissions

## Smart Contracts

### 1. Asset Manager Verification (`asset-manager-verification.clar`)
- Verifies asset managers with different verification levels
- Manages manager credentials and permissions
- Provides read-only functions to check verification status

### 2. Asset Cataloging (`asset-cataloging.clar`)
- Catalogs digital assets with comprehensive information
- Tracks asset ownership and creation history
- Supports asset activation/deactivation

### 3. Metadata Management (`metadata-management.clar`)
- Manages detailed asset metadata including file hashes, sizes, and types
- Supports custom properties and tagging system
- Provides metadata update capabilities with proper authorization

### 4. Usage Tracking (`usage-tracking.clar`)
- Records asset usage events with timestamps and duration
- Tracks usage patterns and analytics
- Maintains user usage history

### 5. Rights Management (`rights-management.clar`)
- Manages asset licensing and permissions
- Supports granular permission systems
- Handles permission granting and revocation

## Key Features

- **Decentralized**: No single point of failure
- **Transparent**: All transactions recorded on blockchain
- **Secure**: Built-in authorization and permission systems
- **Scalable**: Efficient data structures for large-scale usage
- **Flexible**: Customizable metadata and permission systems

## Contract Functions

### Asset Manager Verification
- `verify-manager`: Verify a new asset manager
- `revoke-verification`: Revoke manager verification
- `is-verified-manager`: Check if a manager is verified
- `get-manager-details`: Get manager information

### Asset Cataloging
- `catalog-asset`: Add a new asset to the catalog
- `deactivate-asset`: Deactivate an asset
- `get-asset`: Retrieve asset information
- `get-user-assets`: Get all assets owned by a user

### Metadata Management
- `set-metadata`: Set asset metadata
- `update-metadata`: Update existing metadata
- `get-metadata`: Retrieve asset metadata
- `get-metadata-owner`: Get metadata owner

### Usage Tracking
- `record-usage`: Record asset usage event
- `get-usage-record`: Get usage record details
- `get-asset-usage-count`: Get total usage count for an asset
- `get-user-usage-history`: Get user's usage history

### Rights Management
- `set-asset-rights`: Set asset rights and licensing
- `grant-permission`: Grant permissions to users
- `revoke-permission`: Revoke user permissions
- `get-asset-rights`: Get asset rights information
- `has-permission`: Check if user has specific permission

## Getting Started

1. Deploy the contracts to the Stacks blockchain
2. Verify asset managers using the verification contract
3. Catalog your digital assets
4. Set appropriate metadata and rights
5. Track usage and manage permissions as needed

## Testing

Run the test suite using:

\`\`\`bash
npm test
\`\`\`

## Security Considerations

- All contracts implement proper authorization checks
- Asset ownership is strictly enforced
- Permission systems prevent unauthorized access
- Metadata integrity is maintained through ownership verification

## License

This project is open source and available under the MIT License.
\`\`\`

Let's create the PR details file:

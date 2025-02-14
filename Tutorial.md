# Cheshire Terminal Tutorial

A comprehensive guide to using all features of the Cheshire Terminal.

## DeFi Operations

### Using Morpho Vault

#### Depositing ETH
```bash
1. Connect your wallet using the top-right button
2. Check current ETH vault APY (displayed in the Earn section)
3. Enter ETH amount in the deposit field
4. Click "Deposit" button
5. Confirm transaction (no gas fees thanks to CDP)
6. Wait for confirmation
7. View your deposit in the balance section
```

#### Depositing USDC
```bash
1. Ensure you have USDC in your wallet
2. View USDC vault APY
3. Enter USDC amount
4. Approve USDC spending (first time only)
5. Confirm deposit
6. Monitor transaction status
```

#### Monitoring Your Position
```bash
1. View current balance in the Earn section
2. Check accumulated yield
3. Monitor real-time APY changes
4. Track total value locked
```

### Token Swapping

#### ETH to USDC Swap
```bash
1. In the Swap section, ETH is selected by default
2. Enter ETH amount
3. View estimated USDC output
4. Check price impact and route
5. Click "Swap" button
6. Confirm transaction (gas sponsored)
7. Wait for completion
```

#### USDC to ETH Swap
```bash
1. Click the token selector and choose USDC
2. Enter USDC amount
3. View estimated ETH output
4. Review swap details
5. Confirm swap
6. Track progress
```

## Terminal Commands

### Basic Operations

#### Help and Navigation
```bash
/help                 # View all commands
/clear               # Clear terminal
/time                # Show current time
/history             # View command history
```

#### Wallet Operations
```bash
/connect             # Connect wallet
/disconnect          # Disconnect wallet
/ca                  # View CHESH token address
/explorer            # Open Base explorer
```

### AI Features

#### Code Generation
```bash
# Generate a React component
/code create a React component for a todo list

# Analyze code
/analyze 
function example() {
  // Your code here
}

# Improve code
/improve 
const oldCode = () => {
  var x = 5;
  console.log(x);
}
```

#### AI Chat
```bash
# Chat with DeepChesh
/deep What is the current state of DeFi on Base?

# Use reasoning capabilities
/reason Should I provide liquidity to AMMs?

# General chat
/chat Tell me about Base chain
```

### Voice Commands

#### Basic Voice Usage
```bash
1. Click microphone icon or type /voice
2. Say "Show help" -> Executes /help
3. Say "Connect wallet" -> Executes /connect
4. Say "Show time" -> Executes /time
```

#### DeFi Voice Commands
```bash
1. "Show APY" -> Displays current vault APY
2. "Swap ETH to USDC" -> Opens swap interface
3. "Show balance" -> Displays wallet balance
4. "Open explorer" -> Opens Base explorer
```

## Gas Sponsorship Details

### How It Works
```typescript
// Gas sponsorship is automatic through CDP
// Transaction flow:
1. User initiates transaction
2. CDP intercepts and sponsors gas
3. Transaction is submitted
4. CDP pays gas fee
5. User receives confirmation
```

### Monitoring Gas Usage
```bash
1. View transaction in Base explorer
2. Check "Sponsored by CDP" tag
3. Monitor gas savings
4. Track sponsorship limits
```

## Advanced Features

### Custom Token Integration
```bash
1. Use /ca to get CHESH token address
2. Import into wallet
3. View on explorer
4. Track token transactions
```

### Transaction Monitoring
```bash
1. All transactions appear in terminal history
2. Click explorer links for details
3. Monitor gas sponsorship status
4. Track transaction confirmations
```

## Troubleshooting

### Common Issues
```bash
# Wallet Connection
/connect             # If wallet doesn't connect
/disconnect          # Then reconnect

# Transaction Failed
1. Check gas sponsorship status
2. Verify token approvals
3. Check slippage settings
4. Try again with adjusted parameters
```

### Error Messages
```bash
"Insufficient balance" -> Check wallet funds
"Slippage too high" -> Adjust swap settings
"Transaction failed" -> Check transaction details in explorer
```

## Best Practices

### DeFi Operations
```bash
1. Always check APY before depositing
2. Monitor price impact on swaps
3. Use gas sponsorship efficiently
4. Keep track of your positions
```

### Terminal Usage
```bash
1. Use /history to track commands
2. Clear terminal regularly with /clear
3. Monitor wallet connection status
4. Keep explorer open for verification
```

### Security
```bash
1. Never share private keys
2. Verify transaction details
3. Monitor approval amounts
4. Check contract addresses
```

## Examples

### Complete DeFi Workflow
```bash
1. /connect
2. Check vault APY
3. Deposit ETH
4. Monitor position
5. Swap some ETH to USDC
6. Deposit USDC
7. Track yields
8. /explorer to verify
```

### AI Workflow
```bash
1. /deep Tell me about Base chain
2. /reason Analyze this transaction
3. /code Generate a DeFi interface
4. /analyze Review the generated code
5. /improve Optimize the code
```

### Voice Workflow
```bash
1. Enable voice commands
2. "Show available commands"
3. "Connect wallet"
4. "Show balances"
5. "Open explorer"
6. "Disable voice commands"

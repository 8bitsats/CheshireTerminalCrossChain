# Cheshire Terminal

A powerful terminal interface for Base chain interactions, featuring DeFi integrations, AI capabilities, and voice commands.

## 🌟 Key Features

### 💰 DeFi Components

#### Morpho Vault Integration
- Deposit ETH and USDC into Morpho vaults
- Real-time APY display
- Automatic yield tracking
- Gas-sponsored transactions via CDP
- Balance monitoring and management

#### Token Swapping
- ETH/USDC trading pair
- Gas-sponsored swaps
- 0x Aggregator integration for best rates
- Real-time price updates
- Slippage protection

### 🤖 AI Commands
- `/deep` - Chat with DeepChesh
- `/reason` - Use DeepChesh Reasoner
- `/chat` - Chat with Chesh
- `/code` - Generate code using Claude
- `/analyze` - Analyze code using Claude
- `/improve` - Improve code using Claude

### 🎙️ Voice Integration
- Voice command support
- Real-time speech recognition
- Natural language processing
- Command execution via voice

### 🔗 Blockchain Features
- Base chain integration
- Contract interaction
- Transaction monitoring
- Gas sponsorship
- Explorer integration

## 📚 Detailed Guide

### DeFi Features

#### Morpho Vault
1. Connect your wallet using the top-right button
2. View current APY in the Earn section
3. Enter deposit amount
4. Approve token spending (first time only)
5. Confirm deposit
6. Monitor your position

Benefits:
- Gas-sponsored transactions
- Automatic yield optimization
- Real-time balance updates
- Secure vault contracts

#### Token Swapping
1. Select input token (ETH or USDC)
2. Enter amount to swap
3. View estimated output
4. Confirm swap
5. Track transaction status

Features:
- MEV protection
- Optimal routing
- Price impact warnings
- Transaction sponsorship

### Terminal Commands

#### Basic Commands
- `/help` - Show all available commands
- `/clear` - Clear terminal history
- `/time` - Show current time
- `/echo` - Echo back your message
- `/history` - Show command history

#### Wallet Commands
- `/connect` - Connect wallet
- `/disconnect` - Disconnect wallet
- `/ca` - Show CHESH token contract address
- `/explorer` - Open Base blockchain explorer

#### AI Commands
- `/deep [prompt]` - Engage with DeepChesh AI
- `/reason [prompt]` - Use AI reasoning capabilities
- `/chat [message]` - Chat with Chesh
- `/code [prompt]` - Generate code using Claude
- `/analyze [code]` - Analyze code structure
- `/improve [code]` - Get code improvements

#### Media Commands
- `/voice` - Toggle voice commands
- `/video [prompt] | [image_url]` - Generate video

### Voice Commands
Voice commands can be used for any terminal function:
1. Click the microphone icon or use `/voice`
2. Speak your command
3. Wait for confirmation
4. View results in terminal

### Gas Sponsorship
All DeFi transactions are sponsored through CDP:
- No gas fees for users
- Automatic transaction handling
- MEV protection
- Failed transaction protection

## 🔧 Technical Setup

### Environment Variables
```bash
CDP_API_KEY_NAME=your_key_name
CDP_API_KEY_PRIVATE_KEY=your_private_key
CDP_CLIENT_ID=your_client_id
CDP_RPC_URL=your_rpc_url
NETWORK_ID=base-sepolia
BASESCAN_API_KEY=your_basescan_key
```

### Network Configuration
```typescript
{
  id: 8453,
  name: 'Base',
  rpcUrls: {
    default: {
      http: ['https://mainnet.base.org']
    }
  },
  nativeCurrency: {
    name: 'Ether',
    symbol: 'ETH',
    decimals: 18
  }
}
```

## 🚀 Quick Start

1. Connect your wallet
2. Try a basic command: `/help`
3. Explore DeFi features:
   - Check Morpho vault APY
   - Make a test swap
   - Monitor gas sponsorship
4. Test AI capabilities:
   - Generate code with `/code`
   - Chat with `/deep`
5. Try voice commands

## 🔐 Security

- All contracts are audited
- Gas sponsorship is rate-limited
- Wallet connections are secure
- Transaction signing is local
- MEV protection enabled

## 🤝 Support

For help:
- Use `/help` command
- Check transaction status in explorer
- Monitor gas sponsorship in CDP dashboard
- View vault positions in Morpho interface

## 🔄 Updates

The terminal is regularly updated with:
- New DeFi integrations
- Enhanced AI capabilities
- Additional voice commands
- Improved gas optimizations
- Security enhancements

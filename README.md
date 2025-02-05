# Payman Documentation

Welcome to the official documentation for Payman - the payment infrastructure for AI Agents. This repository contains our public documentation, API references, and integration guides.

## 🏗 Documentation Structure

- `/main` - Core concepts and getting started guides
- `/api-reference` - Complete API documentation and endpoints
- `/webhook` - Webhook integration and event handling
- `/capabilities` - Detailed feature documentation

## 🚀 Local Development

This documentation site is built using [Mintlify](https://mintlify.com/). To run it locally:

```bash
# Install Mintlify CLI
npm i -g mintlify

# Start development server
mintlify dev
```

The development server will start at `http://localhost:3000`.

## ✍️ Contributing

We welcome contributions to improve our documentation! Here's how you can help:

1. Fork this repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Test locally using `mintlify dev`
5. Commit your changes (`git commit -am 'Add new content'`)
6. Push to the branch (`git push origin feature/improvement`)
7. Create a Pull Request

### Writing Guidelines

- Use clear, concise language
- Include code examples where relevant
- Follow the existing document structure
- Test all code samples
- Update the navigation in `mint.json` if adding new pages

### Code Examples

When adding code examples:
- Include both Node.js and Python examples where applicable
- Use real-world scenarios
- Include comments for complex operations
- Follow our code style guidelines

## 🔍 Preview Changes

All pull requests automatically generate a preview deployment. Look for the "mintlify/deploy" check in your PR for the preview URL.

## 📝 License

This documentation is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💬 Need Help?

- [Open an issue](https://github.com/PaymanAI/documentation/issues)
- [Contact support](mailto:support@paymanai.com)
- [Follow us on Twitter](https://twitter.com/PaymanAI)

### Payment Types

- ACH bank transfers
- Agent-to-agent instant transfers
- Crypto payments (Coming Soon)

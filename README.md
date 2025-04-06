# Privacy Policy for Text Summarizer with Pegasus

**Last Updated: April 6, 2025**

## Introduction

This Privacy Policy describes how the Text Summarizer with Pegasus browser extension ("we", "our", or "the extension") collects, uses, and shares information when you use our service. We respect your privacy and are committed to protecting your personal data.

## Information We Collect

### Text Selection Data

When you select text on a webpage and use our summarization feature:

- The selected text is temporarily processed by our extension
- The selected text is sent to the Hugging Face Inference API for summarization
- We do not store the selected text or its summary on our servers

### Settings Data

The extension stores the following information locally on your device:

- Your preferred summarization method (AI-generated or extractive)
- Your Hugging Face API token (if you choose to provide one)

This data is stored locally using your browser's storage APIs and is not transmitted to our servers.

## How We Use Your Information

### Text Summarization

We use the text you select solely for the purpose of generating a summary using either:

- The Hugging Face Inference API (specifically the Pegasus-XSum model)
- A local extractive summarization algorithm that runs entirely in your browser

### API Communication

If you use the AI-generated summarization option:

- Your selected text is sent to the Hugging Face Inference API (https://api-inference.huggingface.co)
- If you've provided your own API token, that token is used for authentication
- If you haven't provided a token, our default token is used

## Data Sharing and Third Parties

### Third-Party Services

The extension uses the following third-party services:

- **Hugging Face Inference API**: When you use the AI-generated summarization option, your selected text is sent to Hugging Face's servers. Their privacy policy applies to their processing of this data and can be found at: https://huggingface.co/privacy

### Data Sharing

We do not:
- Sell your personal information
- Store your selected text or summaries
- Share any data with advertising networks
- Use your data for behavioral tracking or profiling

## Data Security

We implement appropriate technical measures to protect your information:

- All API communications are encrypted using HTTPS
- API tokens are stored securely in your browser's local storage
- The extension requests only the minimum permissions required for functionality

## Your Rights and Choices

You have the right to:

- Use the offline extractive summarization option if you prefer not to send data to external APIs
- Delete your local extension data at any time by clearing browser storage
- Provide your own Hugging Face API token or use our default token

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices or for other operational, legal, or regulatory reasons. The updated version will be indicated by an updated "Last Updated" date.

## Children's Privacy

The extension is not intended for use by children under the age of 13. We do not knowingly collect personally identifiable information from children under 13.

## Contact Us

If you have any questions about this Privacy Policy or our practices, please contact us at:

[Your Email Address or Contact Information]

## Governing Law

This Privacy Policy is governed by and construed in accordance with the laws of [Your Country/State].

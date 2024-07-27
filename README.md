<a href="https://aptos.dev">
	<img width="100%" src="./.assets/aptos_banner.png" alt="Aptos Banner" />
</a>

# Awesome Alinks 🌟

Welcome to the Awesome Alinks repository! This space is dedicated to showcasing innovative Alinks (Aptos Links) on the Aptos blockchain. Let's explore the world of Alinks together.

## 🌐 Understanding Alinks

Alinks are the Aptos equivalent of Solana Blinks (Blockchain Links), enabling you to use Aptos applications directly within Twitter through embedded cards. These are essentially Twitter Cards tailored for the Aptos ecosystem, providing a seamless web3 experience right from your tweets.

Under the hood, Alinks are just [Twitter Cards](https://developer.x.com/en/docs/twitter-for-websites/cards/overview/abouts-cards).

## 🎯 Repository Goals
#### 1. Highlight Exciting Alinks on Aptos:
Discover and explore unique and useful Alinks.
#### 2. Guide on Implementing Alinks:
Learn how to easily create and embed Alinks for any Aptos application.

## 📝 Featured Alinks

Here's a list of some cool Alinks on Aptos:

- **Joule Finance Cross Chain Swap**

  - Live Slink Tweet: []()
  - Official Application Website: [joule.finance](joule.finance)


## 🔐 Security Disclaimer

**Important**: Interacting with web3 applications involves risks. Inclusion in this list does not guarantee security or the absence of vulnerabilities. Always exercise caution, conduct thorough research, and understand the potential risks before engaging with any decentralized application.

## 🤝 Contribute to the List

We welcome contributions from the community! If you know of a cool Alink that isn't listed here, please submit a pull request to help expand our collection.

## 🔧 How to Create an Alink

### Step 1: Add Twitter Card Metadata
Incorporate the following meta tags into the <head> section of your application's HTML:

```html
<meta name="twitter:card" content="player" />
<meta name="twitter:site" content="@YourTwitterHandle" />
<meta name="twitter:title" content="Your App Title" />
<meta name="twitter:description" content="Brief description of your app" />
<meta
  name="twitter:player"
  content="https://your-domain.com/twitter-card.html"
/>
<meta name="twitter:player:width" content="360" />
<meta name="twitter:player:height" content="560" />
<meta
  name="twitter:image"
  content="https://your-domain.com/preview-image.png"
/>
```

### Step 2: Enhance with Open Graph Meta Tags
For better sharing across social media platforms, add Open Graph meta tags to your HTML:

```html
<meta property="og:url" content="YOUR_PAGE_URL" />
<meta property="og:title" content="Your Title Here" />
<meta property="og:description" content="Your description here" />
<meta property="og:image" content="URL_TO_YOUR_IMAGE" />
```

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

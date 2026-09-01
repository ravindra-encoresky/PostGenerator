# Social Post Generator

Generate LinkedIn and Instagram posts instantly using your own AI API key. No backend, no data collection — everything runs in your browser.

## Features

- 🤖 **Multi-API Support**: Google Gemini, OpenAI, or Hugging Face
- 📱 **Platform-Specific**: Auto-formats content for LinkedIn and Instagram
- 🎨 **Live Preview**: See how your posts will look before sharing
- 💾 **Export Options**: Copy to clipboard or download as text
- 🌙 **Dark Mode**: Built-in theme toggle
- 🔒 **Privacy First**: API keys never leave your browser

## Quick Start

1. Get a free API key from one of these services:
   - [Google Gemini](https://makersuite.google.com/app/apikey) (Free tier available)
   - [OpenAI](https://platform.openai.com/api-keys) (Free trial credits)
   - [Hugging Face](https://huggingface.co/settings/tokens) (Free tier)

2. Open `index.html` in your browser

3. Paste your API key, describe your content idea, and generate!

## Supported Platforms

- **LinkedIn**: Professional, inspiring tone (3000 char limit)
- **Instagram**: Casual, creative tone (2200 char limit)

## Tone Options

- Professional & Inspiring
- Casual & Friendly
- Humorous & Witty
- Motivational & Energetic
- Educational & Informative

## Privacy

Your API key is only used in your browser and never transmitted to any server (except to your chosen AI provider's API). No data is stored or logged.

## Deploy to GitHub Pages

1. Go to repository Settings → Pages
2. Select `main` branch as source
3. Your site will be live at `https://yourusername.github.io/PostGenerator`

## How It Works

The generator:
1. Takes your input (topic + tone)
2. Creates platform-specific prompts for LinkedIn and Instagram
3. Sends them to your chosen AI API via your key
4. Formats the results with character counts and export options

## Contributing

Feel free to fork, modify, and improve! Common enhancements:
- Add more tone options
- Support for more platforms (TikTok, Twitter, etc.)
- Image generation integration
- Post scheduling features

## License

MIT

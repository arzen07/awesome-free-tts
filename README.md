# Awesome Free TTS

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of free Text-to-Speech (TTS) services, libraries, and tools that provide high-quality speech synthesis capabilities.

A comprehensive collection of free TTS solutions for developers, content creators, accessibility advocates, and anyone looking to convert text to speech without breaking the bank.

## Contents

- [Web-Based TTS Services](#web-based-tts-services)
- [Open Source TTS Libraries](#open-source-tts-libraries)
- [API Services](#api-services)
- [Mobile Apps](#mobile-apps)
- [Browser Extensions](#browser-extensions)
- [Accessibility Tools](#accessibility-tools)
- [Research & Academic](#research--academic)
- [Contributing](#contributing)

## Web-Based TTS Services

### General & AI-Powered Voice Generators

- **[ElevenLabs](https://elevenlabs.io/)** - AI-powered TTS with incredibly natural voices and voice cloning capabilities. Free tier: 10,000 characters per month, non-commercial use, access to multiple voices.
- **[Natural Reader](https://www.naturalreaders.com/)** - High-quality TTS with natural-sounding voices and support for multiple languages. Free tier: Unlimited use of free voices, 20 minutes/day with premium voices, supports various document formats (PDF, Docx, etc.), OCR for reading from images.
- **[Play.ht](https://play.ht/)** - Advanced AI TTS with 600+ voices across 60+ languages. Free tier: 5,000 words per month, requires attribution, non-commercial use, access to premium and ultra-realistic AI voices.
- **[Murf.ai](https://murf.ai/)** - AI voice generator with studio-quality voices and extensive customization options. Free tier: 10 minutes of voice generation, no downloads, non-commercial use, focus on studio-quality output for presentations and videos.
- **[Speechify](https://speechify.com/)** - AI-powered TTS with natural-sounding voices and document reading capabilities. Free tier: Basic TTS with standard voices, reads web pages, documents, and imports text, available as web service, mobile app, and browser extension.
- **[TTSReader](https://ttsreader.com/)** - Browser-based TTS with real-time reading and bookmark features. Free tier: Free for general use with ads, simple browser-based TTS with ability to save progress.
- **[Text2Speech.org](https://text2speech.org/)** - Simple online TTS converter with multiple voice options and download capabilities. Free tier: Completely free with no registration, straightforward tool for quick text-to-speech conversions with downloadable MP3 files.
- **[FreeTTS](https://freetts.com/)** - Free online text-to-speech converter with multiple voices and languages. Free tier: Free online text-to-speech with some character limits per conversion, simple interface with variety of voices and languages.
- **[Uberduck](https://uberduck.ai/)** - AI voice synthesis platform with voice cloning and custom voice creation. Free tier: Free to use with some limitations on voice cloning and API access, popular among content creators and developers.

### Services with More Restricted Free Tiers

- **[Lovo.ai](https://lovo.ai/)** - AI-powered TTS with 500+ voices and emotion control. Free tier: 14-day free trial of the Pro plan, no downloads, offers wide array of voices and emotional controls but free access is temporary.
- **[Synthesia](https://www.synthesia.io/)** - AI video generation with TTS capabilities. Free tier: Create a free demo video, free account has limited features, primarily an AI video generation platform with TTS capabilities.

## Open Source TTS Libraries

### Python Libraries

- **[Coqui TTS](https://github.com/coqui-ai/TTS)** - Deep learning toolkit for text-to-speech synthesis. Mozilla Public License 2.0 (Code), Coqui Public Model License (Non-Commercial for pre-trained models), multilingual support including English, Spanish, French, German, and more. State-of-the-art models with voice cloning capabilities.
- **[Piper TTS](https://github.com/rhasspy/piper)** - Fast, local neural text-to-speech system. MIT License, multilingual support with extensive list of languages and voices available, designed for offline use with high-quality voice synthesis.
- **[gTTS (Google Text-to-Speech)](https://github.com/pndurette/gTTS)** - Python library for Google Translate's text-to-speech API. MIT License, any language supported by Google Translate TTS API, simple library to interface with Google's free TTS service.
- **[pyttsx3](https://github.com/nateshmbhat/pyttsx3)** - Cross-platform text-to-speech library for Python. BSD 3-Clause License, depends on underlying engine (SAPI5, NSSpeech, espeak), works offline and supports multiple TTS engines.
- **[Bark](https://github.com/suno-ai/bark)** - Text-to-audio model with multilingual support. MIT License, multilingual support, generates highly realistic, multilingual speech, music, and sound effects.
- **[Tortoise TTS](https://github.com/neonbjb/tortoise-tts)** - Multi-voice TTS system with advanced voice cloning capabilities. Apache 2.0 License, primarily English, high-quality speech synthesis with natural prosody and focus on voice cloning.
- **[YourTTS](https://github.com/Edresson/YourTTS)** - Zero-shot multi-speaker TTS system. MIT License, English, French, Portuguese, can generate speech in any voice with just a few seconds of audio.
- **[ESPnet](https://github.com/espnet/espnet)** - End-to-end speech processing toolkit. Apache 2.0 License, multilingual support, comprehensive framework for speech synthesis research and development.
- **[PaddleSpeech](https://github.com/PaddlePaddle/PaddleSpeech)** - All-in-one speech processing toolkit. Apache 2.0 License, English, Mandarin Chinese, and others, complete solution for speech recognition, synthesis, and translation from Baidu.
- **[Tacotron 2](https://github.com/NVIDIA/tacotron2)** - Neural network architecture for speech synthesis. Modified BSD License, primarily English, NVIDIA's implementation of Tacotron 2 model for research.
- **[FastSpeech 2](https://github.com/ming024/FastSpeech2)** - Fast, parallel text-to-speech synthesis. MIT License, primarily English, efficient real-time speech generation with high quality.

### Other Programming Languages

- **[Festival](http://www.cstr.ed.ac.uk/projects/festival/)** - General multi-lingual speech synthesis system. Written in C++, X11-like License, mature and stable multilingual speech synthesis system.
- **[eSpeak NG](http://espeak.sourceforge.net/)** - Compact open source software speech synthesizer. Written in C, GPL-3.0-or-later License, compact and efficient software speech synthesizer for many languages.
- **[Flite](http://www.festvox.org/flite/)** - Lightweight speech synthesis engine. Written in C, MIT-like License, small and fast run-time synthesis engine, ideal for embedded systems.
- **[MaryTTS](https://github.com/marytts/marytts)** - Modular open-source platform for building multilingual text-to-speech synthesis. Written in Java, LGPL-3.0-or-later License, comprehensive framework for TTS development.
- **[say.js](https://github.com/Marak/say.js)** - Node.js library for text-to-speech with cross-platform support. Written in JavaScript (Node.js), MIT License, simple Node.js library for text-to-speech with cross-platform support.

## API Services

### APIs with Free Tiers

- **[Google Cloud Text-to-Speech](https://cloud.google.com/text-to-speech)** - Enterprise-grade TTS API with natural-sounding voices. Free tier: 1 million characters per month for WaveNet voices and 4 million for standard voices.
- **[Amazon Polly](https://aws.amazon.com/polly/)** - AWS TTS service with neural voices. Free tier: 5 million characters per month for the first 12 months with AWS Free Tier.
- **[Microsoft Azure Speech Service](https://azure.microsoft.com/en-us/services/cognitive-services/speech-services/)** - Comprehensive speech services including TTS. Free tier: 0.5 million characters per month for neural voices.
- **[IBM Watson Text to Speech](https://www.ibm.com/cloud/watson-text-to-speech)** - AI-powered TTS with customizable voices. Free tier: 10,000 characters per month.
- **[OpenAI TTS API](https://platform.openai.com/docs/guides/text-to-speech)** - High-quality TTS API with natural-sounding voices. Free tier: Available with initial credits upon signing up for OpenAI API key.

## Mobile Apps

- **[Natural Reader](https://apps.apple.com/sr/app/naturalreader-text-to-speech/id1487572960)** - Mobile version of the popular TTS service. Available on iOS and Android, unlimited listening with free voices, document reading, browser integration.
- **[Google Text-to-Speech](https://play.google.com/store/apps/details?id=com.google.android.tts)** - Official Google TTS engine with high-quality voices. Available on Android, default TTS engine for Android providing system-wide TTS capabilities.
- **[@Voice Aloud Reader](https://play.google.com/store/apps/details?id=com.hyperionics.avar)** - Advanced TTS reader with cloud storage support. Available on Android, reads text from various sources including web pages, documents, and emails, free version is ad-supported.
- **[Apple's Built-in TTS](https://support.apple.com/en-us/HT210161)** - Built-in iOS accessibility feature for reading screen content. Available on iOS, "Spoken Content" and "VoiceOver" are powerful system-wide accessibility features.

## Browser Extensions

- **[Read Aloud](https://readaloud.app/)** - Chrome extension for reading web pages aloud. Simple and effective extension that reads web page content with a single click.
- **[Natural Reader](https://chromewebstore.google.com/detail/naturalreader-ai-text-to/kohfgcgbkjodfcfkcackpagifgbcmimk?hl=en&pli=1)** - Browser extension with high-quality voices. Browser extension for the popular TTS service, offering high-quality voices for web content.
- **[Speechify](https://speechify.com/)** - AI-powered TTS with natural-sounding voices. Feature-rich extension that reads web pages, PDFs, and more with natural-sounding voices.
- **[SpeakIt!](https://chromewebstore.google.com/detail/speak-it/amcnjejmdfilapnnfgnhnidhkififadk)** - Text-to-speech Chrome extension. Straightforward extension that reads selected text on a webpage.

## Accessibility Tools

### Screen Readers

- **[NVDA (NonVisual Desktop Access)](https://www.nvaccess.org/)** - Free screen reader for Windows with TTS capabilities. Completely free and open-source screen reader for Microsoft Windows.
- **[VoiceOver](https://www.apple.com/accessibility/vision/)** - Built-in screen reader for Apple devices. Apple's built-in screen reader for macOS, iOS, iPadOS, watchOS, and tvOS.

### Educational Tools

- **[Kurzweil 3000](https://www.kurzweiledu.com/)** - Reading and writing software with TTS capabilities. Comprehensive educational support tool.
- **[Read&Write](https://www.texthelp.com/en-us/products/read-write/)** - Literacy software with TTS features. Educational support for reading and writing.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-tts-service`)
3. Add your contribution following the guidelines below
4. Commit your changes (`git commit -m 'Add amazing TTS service'`)
5. Push to the branch (`git push origin feature/amazing-tts-service`)
6. Open a Pull Request

### Guidelines for Contributions

- **Quality over quantity**: Only suggest services you've personally used and can recommend
- **Clear descriptions**: Explain why each service is awesome and what makes it special
- **Proper categorization**: Place services in the most appropriate category
- **Consistent formatting**: Follow the existing format and style
- **Grammar and spelling**: Ensure all text is grammatically correct and typo-free
- **Valid links**: Verify all links are working and point to the correct resources
- **Verify free tiers**: Ensure services offer substantial free functionality
- **Check licensing**: Verify open source licenses and usage terms

### What Makes a TTS Service Awesome?

- **High voice quality**: Natural-sounding, clear speech synthesis
- **Ease of use**: Simple interface and straightforward functionality
- **Free availability**: Genuinely free or generous free tier
- **Reliability**: Stable service with good uptime
- **Features**: Useful additional features like voice customization, speed control, etc.
- **Accessibility**: Good support for users with disabilities
- **Documentation**: Clear documentation and support resources
- **Community**: Active development and community support

## License

This project is licensed under the Creative Commons Zero v1.0 Universal License - see the [LICENSE](LICENSE) file for details.

---

**Note**: This list focuses on genuinely free TTS services and tools with substantial free tiers. Services that offer only limited trials or require payment for basic functionality have been excluded. Always verify the current terms and conditions of any service before use. 
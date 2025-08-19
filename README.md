# 🎤 AI Voice Transcription for Cursor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![VS Code Marketplace](https://img.shields.io/badge/VS%20Code-Marketplace-blue)](https://marketplace.visualstudio.com/)
[![Version](https://img.shields.io/badge/version-1.0.4-green.svg)](https://github.com/kdeosingh/ai-voice-plugin)

**Code at the speed of thought!** Transform your voice into code, comments, and AI conversations directly within Cursor. Powered by OpenAI's cutting-edge **Whisper** and **GPT** models for lightning-fast, accurate speech recognition and intelligent responses.

> *Imagine coding without breaking your flow - speak your ideas directly into your editor and watch them come to life instantly.*

> *Please install v1.0.5 and up for issues with installing and running the extension.*

## 🚀 Quick Start (3 Steps)

### **Step 1: Configure OpenAI**
1. **Open Command Palette** (`Ctrl+Shift+P`)
2. **Type**: `⚙️ Voice AI Settings`
3. **Set your OpenAI API Key** (get one from [OpenAI](https://platform.openai.com/api-keys))

### **Step 2: Start Recording**  
1. **Look for mic icon** `🎤 Voice AI` in bottom-right status bar
2. **Click the mic icon** to open recording panel
3. **Click "Start Recording"** and speak your thoughts

### **Step 3: Use Your Voice**
- **Record your ideas** → Get instant transcription
- **Click "Send to ChatGPT"** → Get AI feedback and suggestions  
- **Click "Copy"** → Paste transcribed text anywhere in Cursor

> 💡 **Pro Tip**: Use **gpt-4o-transcribe** model and **0.1 temperature** for best accuracy (these are now the defaults!)

---


## ✨ Why AI Voice Transcription?

### 🚀 **Revolutionary Workflow**
- 🗣️ **Talk to Your Editor** - Speak directly to Cursor without switching context
- 🧠 **AI-Powered Accuracy** - OpenAI Whisper understands technical terminology and code
- ⚡ **Instant Flow State** - Never lose your coding momentum switching between typing and thinking
- 🎯 **Purpose-Built for Developers** - Optimized for code, comments, and technical documentation

### 🎤 **Core AI Features**
- 🤖 **OpenAI Integration** - Whisper for transcription, GPT for intelligent responses
- 💬 **ChatGPT Integration** - Send transcriptions directly to ChatGPT for analysis
- 🎵 **Windows System Recording** - Bypasses browser permissions for reliable audio capture
- 📁 **Smart Processing** - Real-time transcription with professional quality
- 🔄 **Seamless Workflow** - Record → Transcribe → Enhance with AI

### 🎛️ **Advanced Intelligence**
- 🔧 **Context-Aware Transcription** - Understands code syntax, function names, and technical terms
- 🌍 **Multi-language Support** - English-optimized with configurable settings
- 🎚️ **Adaptive Quality Controls** - Fine-tune AI behavior for your specific needs
- 📋 **Seamless Integration** - Copy to clipboard or send directly to ChatGPT
- 🛡️ **Intelligent Error Recovery** - Smart handling and user-friendly error messages

## 🚀 Quick Start Guide

### 1. **Installation**

#### From VS Code/Cursor Marketplace
```bash
# Install from the marketplace or download VSIX
code --install-extension kdeosingh.voice-transcription
```

### 2. **AI Setup - Get Your OpenAI API Key**

1. Visit [OpenAI Platform](https://platform.openai.com/api-keys)
2. Create a new API key for transcription
3. Open Cursor Settings (`Ctrl+,` or `Cmd+,`)
4. Search for "**Voice AI**"
5. Paste your API key in **"Voice AI: Openai Api Key"**

### 3. **Start Speaking to Code**

**⚡ Instant Method:**
- **Click the 🎤 Voice AI icon** in the bottom status bar
- **Click "Start Recording"** and speak naturally
- **Click "Stop Recording"** when finished
- **Get instant transcription + ChatGPT analysis**

**🎛️ Advanced Method:**
1. Press `Ctrl+Shift+P` to open command palette
2. Type "**Voice AI**" to see available commands
3. Choose **"🎤 Start Voice Recording"**
4. Speak naturally - the AI handles the rest!

## 🎙️ AI-Powered Features

### **🎤 Windows System Recording**
- **No Browser Permissions** - Uses Windows native recording APIs
- **Professional Quality** - High-fidelity audio capture
- **Reliable Operation** - Never fails due to browser restrictions
- **Instant Processing** - Direct file-based transcription

### **🤖 OpenAI Integration**
- **Whisper Transcription** - Industry-leading speech-to-text accuracy
- **GPT Analysis** - Intelligent feedback and suggestions on your transcriptions
- **Configurable Models** - Choose between Whisper-1 and GPT-4o for different needs
- **Temperature Control** - Adjust AI creativity vs accuracy

### **💬 ChatGPT Workflow**
- **Smart Send** - Click "Send to ChatGPT" to analyze your transcription
- **Real-time Response** - Get intelligent feedback and suggestions
- **Copy Integration** - Easily copy transcriptions or ChatGPT responses
- **Clean Interface** - AI feedback only appears when requested

## ⌨️ Commands & Interface

### **Status Bar Integration**
- **🎤 Voice AI Icon** - Always visible in the bottom-right status bar
- **One-click Access** - Instant recording panel with single click
- **Visual Feedback** - Clear recording states and progress indicators

### **Recording Panel Features**
- **🔴 Start/Stop Recording** - Simple, intuitive controls
- **📝 Transcription Display** - Clean, readable text output
- **📋 Copy Button** - Instant clipboard integration
- **💬 Send to ChatGPT** - Direct AI analysis integration
- **⚙️ Settings Access** - Quick configuration access

## 🧠 AI Configuration & Intelligence

### 🔑 **Core AI Settings**
| Setting | Description | Default | Impact |
|---------|-------------|---------|---------|
| `openaiApiKey` | Your OpenAI API access key | `""` | Enables all AI features |
| `transcriptionModel` | AI transcription model | `"whisper-1"` | Controls transcription quality |
| `gptModel` | ChatGPT model for responses | `"gpt-4o"` | Response intelligence level |
| `temperature` | AI creativity vs accuracy | `0.7` | Lower = more accurate |
| `audioQuality` | Recording quality setting | `"high"` | Audio capture quality |

### 💬 **ChatGPT Models**
| AI Model | Best For | Accuracy | Speed | Cost |
|----------|----------|----------|-------|------|
| **🤖 GPT-4o** | Complex analysis, code review | 98%+ | Fast | Higher |
| **⚡ GPT-4** | Detailed feedback, explanations | 95%+ | Medium | Medium |
| **🔧 GPT-3.5 Turbo** | Quick responses, simple tasks | 90%+ | Very Fast | Lower |

## 🔧 Technical Specifications

### 📊 **Audio Processing**
- **Recording Method**: Windows MCI (Media Control Interface)
- **Format**: WAV (Uncompressed)
- **Quality**: Configurable (Low/Medium/High)
- **Processing**: Direct file-based transcription
- **Cleanup**: Automatic temporary file management

### 🔌 **System Requirements**
- **Editor**: VS Code 1.74.0+ or Cursor latest
- **Platform**: Windows 10/11 (Primary), macOS, Linux (Limited)
- **Internet**: Required for AI processing
- **Hardware**: Microphone access
- **API**: OpenAI account with API access

## 🛠️ Development & Contributing

### **Building from Source**
```bash
# Clone the repository
git clone https://github.com/kdeosingh/ai-voice-plugin.git
cd ai-voice-plugin

# Install dependencies
npm install

# Package the extension
vsce package
```

### **Development Workflow**
```bash
# Install development tools
npm install -g @vscode/vsce

# Package extension
vsce package --allow-star-activation

# Install locally
cursor --install-extension voice-transcription-1.0.4.vsix
```

## 🐛 AI-Powered Troubleshooting

### 🎤 **Audio & AI Issues**

**Problem**: No mic icon visible
**Solutions**:
- ✅ Restart Cursor completely
- ✅ Check extension is installed: `cursor --list-extensions`
- ✅ Verify extension activation in Developer Console

**Problem**: Recording not working
**Solutions**:
- ✅ Check microphone permissions in Windows
- ✅ Try running Cursor as administrator
- ✅ Verify PowerShell execution policy

**Problem**: AI transcription failing
**Solutions**:
- ✅ Verify OpenAI API key is set correctly
- ✅ Check API key has sufficient credits
- ✅ Test API connection with simpler models

### ⚠️ **Common Error Messages**

| Error | Cause | Solution |
|-------|-------|----------|
| "OpenAI API key not configured" | Missing API key | Add valid OpenAI API key in settings |
| "Audio file not found" | Recording failed | Check microphone permissions |
| "Failed to start recording" | System issue | Run Cursor as administrator |

## 🔒 Privacy & Security

### 🛡️ **Data Handling**
- **Local Recording**: Audio captured locally in your system
- **Secure Processing**: HTTPS encrypted transmission to OpenAI
- **No Storage**: Audio files automatically deleted after processing
- **Privacy First**: Only transcription content sent to AI, no personal data

### 🔐 **Security Best Practices**
- 🔑 Store API keys securely in Cursor settings only
- 🚫 Never commit API keys to version control
- 📊 Monitor OpenAI API usage and costs
- 🛡️ Use environment variables for production deployments

## 📈 AI Use Cases for Developers

### 👨‍💻 **Code Development**
- 🗣️ **Voice-driven coding**: Speak function implementations naturally
- 📝 **Smart comments**: AI-enhanced documentation generation
- 🐛 **Bug descriptions**: Dictate detailed issue reports
- 📋 **Code reviews**: Voice notes for review feedback

### 🎯 **Technical Documentation**
- 📚 **API documentation**: Speak technical specifications
- 🔧 **Setup guides**: Voice-driven installation instructions
- 💡 **Architecture notes**: Dictate system design decisions
- 📊 **Meeting notes**: Transcribe technical discussions

### 🚀 **Productivity Workflows**
- ⚡ **Rapid prototyping**: Voice your ideas into structured text
- 🧠 **Brainstorming**: Capture creative solutions instantly
- 📧 **Communication**: Draft technical emails and messages
- 🎯 **Task planning**: Voice your development roadmap

## 🤝 Contributing

We welcome contributions to make AI voice transcription even better!

### **Enhancement Ideas**
- 🧠 Additional AI model integrations
- 🎨 Custom voice command recognition
- 🔧 Enhanced code syntax understanding
- 🌍 Multi-language AI improvements

### **Development Setup**
1. Fork the repository on GitHub
2. Create a feature branch (`git checkout -b feature/amazing-enhancement`)
3. Implement your improvements
4. Test thoroughly with various voice inputs
5. Submit a pull request with detailed description

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- 🤖 **OpenAI** for the revolutionary Whisper and GPT APIs
- 🛠️ **VS Code & Cursor teams** for excellent extension frameworks
- 👥 **Developer community** for feedback and enhancement ideas
- 🎤 **Voice technology pioneers** for advancing speech recognition

## 📞 Support & Community

- 📧 **Issues**: [GitHub Issues](https://github.com/kdeosingh/ai-voice-plugin/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/kdeosingh/ai-voice-plugin/discussions)
- 📖 **Documentation**: Complete guide in this README
- 🤖 **AI Tips**: Check troubleshooting for optimization tips

---

**🤖 Ready to code with AI-powered voice?** Install the extension and start speaking your ideas into reality!

[![Install Now](https://img.shields.io/badge/Install%20Now-VS%20Code%20Marketplace-blue?style=for-the-badge)](https://marketplace.visualstudio.com/)

---

*Built with 🤖 AI and ❤️ for the future of voice-driven development. Transform your workflow today! 🚀*

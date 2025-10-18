# Claude Translation Skill

A professional cross-language translation skill for Claude AI based on the **"Faithfulness-Fluency-Elegance" (信达雅)** translation framework.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude](https://img.shields.io/badge/Claude-Skill-blue.svg)](https://claude.ai)

## 🌟 Features

- **Three-Layer Output Structure**: Core translation + Key terms explanation + Background context
- **Universal Language Support**: Works with any language pair
- **Text-Type Adaptive**: Optimized strategies for literary, academic, business, technical, and marketing content
- **Cultural Bridge**: Deep cultural context and cross-linguistic analysis
- **Professional Quality**: Based on established translation theory and best practices

## 📋 What You Get

### Layer 1: Core Translation
Fluent, natural translation in the target language that preserves the tone and style of the original.

### Layer 2: Key Terms Explanation
Detailed analysis of 2-4 critical terms including:
- Original meaning and cultural connotations
- Translation strategy rationale
- Alternative translations considered

### Layer 3: Background Context
Cultural, historical, and linguistic context including:
- Cross-cultural communication considerations
- Author's intent and implied meanings
- Overall translation strategy

## 🚀 Quick Start

### Installation

1. **Download the skill package**
   - Download `translation.zip` from the [Releases](../../releases) page
   - Or clone this repository and use the `translation.zip` file

2. **Upload to Claude**
   - Start a new conversation with Claude
   - Upload the `translation.zip` file
   - Say: "Please install this translation skill"

3. **Start translating!**
   ```
   Translate this English text to Chinese:
   "To be or not to be, that is the question."
   ```

### Alternative: Direct Use

You can also upload the zip file and immediately use it:
```
Use this skill to translate the following text: [your text]
```

## 💡 Usage Examples

### Basic Translation
```
Use the translation skill to translate this Japanese to English:
「一期一会」
```

### Academic Translation
```
This is an academic paper abstract. Please translate it using 
the translation skill, paying attention to terminology accuracy.

[Abstract text]
```

### Literary Translation
```
Please use the translation skill to translate this Shakespeare passage,
preserving the poetic beauty and rhythm.

[Original text]
```

### Marketing Localization
```
Translate this marketing copy from English to Spanish, Japanese, 
and French using the translation skill. Focus on localization 
rather than literal translation.

[Marketing text]
```

## 🎯 Translation Framework

This skill implements a balanced approach to translation:

### Faithfulness (信)
- Accurate conveyance of original meaning
- Preservation of author's intent and tone
- Faithful to the source context

### Fluency (达)
- Natural target language expressions
- Reader-centered approach
- Cultural gap bridging

### Elegance (雅)
- Stylistic preservation
- Aesthetic value retention
- Rhetorical device adaptation

## 📚 Supported Text Types

The skill automatically adapts its strategy based on text type:

| Text Type | Priority | Key Focus |
|-----------|----------|-----------|
| Literary | Elegance ≥ Fluency > Faithfulness | Imagery, rhythm, style |
| Academic | Faithfulness > Fluency > Elegance | Terminology, logic |
| Business/Legal | Faithfulness ≥ Fluency > Elegance | Precision, clarity |
| Technical | Faithfulness = Fluency > Elegance | Accuracy, consistency |
| Marketing | Fluency = Elegance > Faithfulness | Impact, localization |

## 🛠️ Technical Details

### Skill Structure
```
translation/
└── SKILL.md    # Main skill file with translation framework
```

### Compatibility
- ✅ Works with all Claude versions supporting skills
- ✅ Can be combined with other skills
- ✅ Supports batch translation tasks

### File Format
- Standard Claude skill format with YAML frontmatter
- Validated with official Claude skill-creator tools
- Minimal context footprint (6.5KB)

## 📖 Documentation

- [Installation Guide](docs/installation.md) - Detailed installation instructions
- [Usage Guide](docs/usage.md) - Comprehensive usage examples
- [Translation Theory](docs/theory.md) - Background on the translation framework
- [FAQ](docs/faq.md) - Frequently asked questions

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Report Issues**: Found a bug or have a suggestion? [Open an issue](../../issues)
2. **Submit Pull Requests**: Improvements to the skill are appreciated
3. **Share Examples**: Show us how you're using the skill
4. **Spread the Word**: Star ⭐ the repository if you find it useful

### Development

To modify the skill:

1. Edit `translation/SKILL.md`
2. Test with Claude
3. Package using the skill-creator tools (if available)
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Based on the traditional Chinese translation theory of "信达雅" (Faithfulness-Fluency-Elegance)
- Built using Claude's official skill-creator framework
- Inspired by professional translation best practices

## 📞 Contact & Support

- **Issues**: Use the [GitHub Issues](../../issues) page
- **Discussions**: Join the [Discussions](../../discussions) section
- **Updates**: Watch the repository for updates

## 🗺️ Roadmap

- [x] Initial release with core translation framework
- [ ] Add example translations showcase
- [ ] Create video tutorial
- [ ] Add support for specialized domains (legal, medical, etc.)
- [ ] Community translation quality evaluation

## ⭐ Star History

If you find this skill useful, please consider giving it a star!

---

**Made with ❤️ for the Claude community**

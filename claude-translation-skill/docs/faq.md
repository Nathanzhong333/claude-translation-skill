# Frequently Asked Questions (FAQ)

## General Questions

### What is the Claude Translation Skill?

The Claude Translation Skill is a specialized add-on for Claude AI that provides professional-quality translation based on the "Faithfulness-Fluency-Elegance" (信达雅) framework. Unlike simple translation, it provides three layers of output: core translation, key terms explanation, and background context.

### Is this free to use?

Yes! The skill itself is completely free and open-source under the MIT License. You just need access to Claude AI.

### What languages are supported?

The skill works with any language pair that Claude can handle. This includes but is not limited to:
- English, Chinese (Simplified & Traditional), Japanese, Korean
- Spanish, French, German, Italian, Portuguese
- Russian, Arabic, Hindi, and many more

### How is this different from regular Claude translation?

| Feature | Regular Translation | Translation Skill |
|---------|-------------------|-------------------|
| Output Structure | Single layer | Three layers |
| Cultural Context | Basic | Detailed analysis |
| Terminology | No explanation | 2-4 key terms explained |
| Strategy Explanation | None | Comprehensive |
| Text Type Adaptation | Generic | Specialized by type |

## Installation & Setup

### Do I need to install the skill in every new conversation?

Yes. Skills are session-based in Claude. You'll need to upload and install the skill at the start of each new conversation where you want to use it.

**Tip**: Keep the `translation.zip` file handy for quick re-installation.

### Can I use the skill without "installing" it?

Yes! You can upload the zip file and immediately say "Use this skill to translate..." without a formal installation step.

### How much storage space does it take?

Very minimal - the skill is only 6.5KB, designed to be lightweight and efficient.

### Can I modify the skill for my needs?

Absolutely! The skill is open-source. You can:
1. Extract the zip file
2. Edit `SKILL.md`
3. Re-package it
4. Share your version (please credit the original)

## Usage Questions

### How do I trigger the skill?

Use phrases like:
- "Use the translation skill to translate..."
- "Translate this with the translation skill..."
- "Please apply the translation skill to..."

### Can I use it with other skills?

Yes! The translation skill works great with other skills. For example:
- Translate → docx skill (create bilingual document)
- Translate → pptx skill (create translated presentation)
- Web search → translate (translate current information)

### Does it work for technical/specialized content?

Yes! The skill adapts to different text types:
- Academic: Prioritizes terminology accuracy
- Legal: Eliminates ambiguity
- Medical: Ensures precision
- Literary: Preserves style and beauty
- Business: Professional clarity

### Can I translate multiple documents at once?

Yes, you can batch translate. Just specify that you want consistent terminology across all documents.

### What if I don't need all three layers?

You can request specific layers:
```
Just give me the core translation without the detailed analysis
```

or

```
Focus on the key terms explanation for this text
```

## Output & Quality

### Why does the translation sometimes differ from literal meaning?

The skill prioritizes natural target language expressions over word-for-word translation. The Key Terms section explains why specific choices were made.

### How can I ensure terminology consistency?

Provide a glossary:
```
Use these specific translations:
- "user" → "用户"
- "account" → "账户"
```

### What if I disagree with a translation choice?

The Background Context explains the rationale. You can:
1. Ask for an alternative translation
2. Request a more literal version
3. Specify your preference for future translations

### Can it handle idioms and cultural references?

Yes! This is one of the skill's strengths. Idioms and cultural references get:
- Natural equivalent in target language (Core Translation)
- Literal meaning explanation (Key Terms)
- Cultural background (Background Context)

## Technical Questions

### What's the "Faithfulness-Fluency-Elegance" framework?

It's a classical Chinese translation theory (信达雅):
- **Faithfulness (信)**: Accurate to original meaning
- **Fluency (达)**: Natural in target language
- **Elegance (雅)**: Preserves aesthetic quality

The skill balances these three principles based on text type.

### How does text type detection work?

You can specify the text type explicitly, or Claude will infer it from context. Different types get different priority orders:
- Literary: Elegance > Fluency > Faithfulness
- Academic: Faithfulness > Fluency > Elegance
- Marketing: Fluency = Elegance > Faithfulness

### Is there a word/character limit?

Claude's general message limits apply. For very long documents:
- Break into sections
- Translate sequentially
- Ask for terminology consistency

### Can I automate this?

The skill is designed for interactive use with Claude. For automation, you'd need to use the Claude API with the skill file.

## Comparison Questions

### How does this compare to Google Translate?

| Feature | Google Translate | Translation Skill |
|---------|-----------------|-------------------|
| Speed | Instant | Conversational |
| Context | Limited | Deep analysis |
| Explanation | None | Three-layer |
| Adaptation | Fixed | Text-type aware |
| Cultural insight | Minimal | Extensive |
| Best for | Quick lookup | Professional work |

### Should I use this instead of human translators?

The skill is a powerful tool but:
- ✅ Excellent for: First drafts, understanding, learning, quick translations
- ⚠️ Consider human review for: Legal contracts, medical documents, published works
- 🤝 Best approach: Use skill for draft, human for final review

### How does it compare to other AI translation tools?

The skill's unique features:
- Three-layer output structure
- Explicit translation strategy
- Cultural context explanation
- Text-type adaptation
- Educational value (learn from explanations)

## Troubleshooting

### The skill isn't working

**Checklist:**
- [ ] Did you upload the file?
- [ ] Did you explicitly mention "translation skill"?
- [ ] Is the file corrupted? (Re-download)
- [ ] Try re-uploading and reinstalling

### Output format is wrong

Try being more specific:
```
Use the translation skill with this format:
【核心译文】
...
【重点词解】
...
【背景解读】
...
```

### Translation seems off

This could be due to:
- Ambiguous source text (provide more context)
- Specialized terminology (provide glossary)
- Cultural nuances (specify target audience)

Ask Claude to explain the translation choices or provide alternatives.

### Can't find the uploaded file

Files are session-specific. If you start a new conversation, you'll need to re-upload.

## Contributing & Community

### How can I contribute?

- Report issues on GitHub
- Submit improved versions
- Share usage examples
- Translate the documentation
- Help other users

### Where can I get help?

- [GitHub Issues](https://github.com/YOUR-USERNAME/claude-translation-skill/issues)
- [Discussions](https://github.com/YOUR-USERNAME/claude-translation-skill/discussions)
- Review the [Usage Guide](usage.md)

### Can I create a derivative work?

Yes! Under the MIT License, you can:
- Modify the skill
- Create specialized versions
- Distribute your version
- Use commercially

Just include the original license and attribution.

### How can I share my translations?

We'd love to see examples! Share in:
- [GitHub Discussions](https://github.com/YOUR-USERNAME/claude-translation-skill/discussions)
- Social media (tag the project)
- Blog posts (link back to the repo)

## Future Development

### What features are planned?

See the [Roadmap](../README.md#-roadmap) in the main README.

### Can I request features?

Absolutely! [Open an issue](https://github.com/YOUR-USERNAME/claude-translation-skill/issues) with:
- Feature description
- Use case
- Example of how it would work

### Is there a premium version?

No. This skill is and will remain free and open-source.

---

## Still have questions?

- 📖 Read the [Usage Guide](usage.md)
- 💡 Check [Example Translations](../examples/)
- 🐛 [Open an issue](https://github.com/YOUR-USERNAME/claude-translation-skill/issues)
- 💬 [Start a discussion](https://github.com/YOUR-USERNAME/claude-translation-skill/discussions)

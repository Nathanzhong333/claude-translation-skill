# Changelog

All notable changes to the Claude Translation Skill will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2025-10-18

### Added
- Initial release of Claude Translation Skill
- Three-layer output structure (Core Translation, Key Terms, Background Context)
- "Faithfulness-Fluency-Elegance" (信达雅) translation framework
- Text-type adaptive strategies for:
  - Literary translation
  - Academic translation
  - Business/Legal translation
  - Technical documentation
  - Marketing copy
- Translation decision tree for handling difficult expressions
- Common pitfall avoidance guidelines
- Quality checklist
- Comprehensive documentation:
  - Installation guide
  - Usage guide with examples
  - FAQ
  - Translation theory background
- Example translations across 6 different scenarios
- MIT License

### Technical Details
- Skill size: 6.5KB (optimized for minimal context usage)
- Format: Standard Claude skill with YAML frontmatter
- Validated with official skill-creator tools
- Packaged as distribution-ready zip file

## [Unreleased]

### Planned
- Additional language-specific optimization guides
- More example translations
- Video tutorials
- Community translation showcase
- Integration examples with other skills
- Specialized domain variants (medical, legal, technical)

---

## Version History

### Version Numbering

We use semantic versioning (MAJOR.MINOR.PATCH):
- **MAJOR**: Incompatible API changes or major restructuring
- **MINOR**: New features, backward-compatible
- **PATCH**: Bug fixes, documentation updates

### How to Upgrade

1. Download the new `translation.zip` from releases
2. Upload to Claude
3. Say: "Please update my translation skill"

### Support

- Current version: 1.0.0
- Supported: Yes
- End of life: N/A

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for how to suggest changes that may appear in future versions.

## Release Notes Template

For future releases:

```markdown
## [X.Y.Z] - YYYY-MM-DD

### Added
- New features

### Changed
- Changes to existing features

### Deprecated
- Features marked for removal

### Removed
- Removed features

### Fixed
- Bug fixes

### Security
- Security improvements
```

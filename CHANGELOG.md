# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-02-25

### Added
- Initial release
- Complete Diataxis theoretical framework (based on https://diataxis.fr)
- Four documentation types detailed (Tutorial, How-to Guide, Reference, Explanation)
- Diataxis Compass decision tool
- Diataxis Map theoretical model
- Quality assessment framework (Functional Quality + Deep Quality)
- Common mistakes documentation
- Four type language style guide
- 8 scenario-based templates:
  - `template-tutorial.md`
  - `template-how-to.md`
  - `template-reference.md`
  - `template-explanation.md`
  - `template-troubleshooting.md`
  - `template-best-practices.md`
  - `template-learning-notes.md`
  - `template-exploration.md`
- 4 quality checklists:
  - `checklist-tutorial.md`
  - `checklist-how-to.md`
  - `checklist-reference.md`
  - `checklist-explanation.md`
- Document type diagnosis script (`scripts/diagnose.py`)
- Output handler script (`scripts/output-handler.py`) with auto-detection
- Output platform reference document
- Tool availability check mechanism
- Mandatory pre-task checklist
- Error logging mechanism

### Changed
- Restructured directory: moved checklist files from `references/` to dedicated `checklist/` directory
- Updated checklist reference paths in SKILL.md
- Improved output method documentation, clarified MCP/mcporter usage
- Updated script paths to use relative paths (avoid hardcoded absolute paths)
- Extended trigger words list to 40+ items (Chinese and English)
- Rewrote all files in English (maintain theoretical purity)
- Improved SKILL.md pre-writing questions (clarified language preference and output method)

### Fixed
- Fixed script path dependency issues
- Fixed MCP configuration path documentation
- Fixed insufficient skill trigger words (expanded from 10+ to 40+)
- Fixed inaccurate document type diagnosis

---

**Last Updated**: 2026-02-25  
**Maintainer**: Zhua Zhua  
**Theory Source**: https://diataxis.fr

# @mastra/voice-speechify

## 0.1.1-alpha.1

### Patch Changes

- Updated dependencies [ed55f1d]
  - @mastra/core@0.4.3-alpha.1

## 0.1.1-alpha.0

### Patch Changes

- Updated dependencies [06aa827]
  - @mastra/core@0.4.3-alpha.0

## 0.1.0

### Patch Changes

- f477df7: deprecate @mastra/speech-speechify for @mastra/voice-speechify
- Updated dependencies [7fceae1]
- Updated dependencies [8d94c3e]
- Updated dependencies [99dcdb5]
- Updated dependencies [6cb63e0]
- Updated dependencies [f626fbb]
- Updated dependencies [e752340]
- Updated dependencies [eb91535]
  - @mastra/core@0.4.2

## 0.1.0-alpha.4

### Patch Changes

- Updated dependencies [8d94c3e]
- Updated dependencies [99dcdb5]
- Updated dependencies [e752340]
- Updated dependencies [eb91535]
  - @mastra/core@0.4.2-alpha.2

## 0.1.0-alpha.3

### Patch Changes

- Updated dependencies [6cb63e0]
  - @mastra/core@0.4.2-alpha.1

## 0.1.0-alpha.2

### Patch Changes

- f477df7: deprecate @mastra/speech-speechify for @mastra/voice-speechify

## 0.1.0 (2024-XX-XX)

This package replaces the deprecated @mastra/speech-speechify package. All functionality has been migrated to this new package with a more consistent naming scheme.

### Changes from @mastra/speech-speechify

- Package renamed from @mastra/speech-speechify to @mastra/voice-speechify
- API changes:
  - `SpeechifyTTS` class renamed to `SpeechifyVoice`
  - `generate()` and `stream()` methods combined into `speak()`
  - `voices()` method renamed to `getSpeakers()`
  - Constructor configuration simplified
  - Added support for text stream input
- All core functionality remains the same
- Import paths should be updated from '@mastra/speech-speechify' to '@mastra/voice-speechify'

For a complete history of changes prior to the rename, please see the changelog of the original package.

# @mastra/voice-elevenlabs

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

- f626fbb: deprecate @mastra/speech-deepgram for @mastra/voice-deepgram
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

- f626fbb: deprecate @mastra/speech-deepgram for @mastra/voice-deepgram
- Updated dependencies [7fceae1]
- Updated dependencies [f626fbb]
  - @mastra/core@0.4.2-alpha.0

## 0.1.0 (2024-XX-XX)

This package replaces the deprecated @mastra/speech-elevenlabs package. All functionality has been migrated to this new package with a more consistent naming scheme.

### Changes from @mastra/speech-elevenlabs

- Package renamed from @mastra/speech-elevenlabs to @mastra/voice-elevenlabs
- API changes:
  - `ElevenLabsTTS` class renamed to `ElevenLabsVoice`
  - `generate()` method renamed to `speak()`
  - `voices()` method renamed to `getSpeakers()`
  - Constructor configuration simplified
- All core functionality remains the same
- Import paths should be updated from '@mastra/speech-elevenlabs' to '@mastra/voice-elevenlabs'

For a complete history of changes prior to the rename, please see the changelog of the original package.

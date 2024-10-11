# Accessibility Testing with VoiceOver on macOS

This document provides instructions for performing accessibility tests using VoiceOver, the built-in screen reader on macOS. Follow these steps to test the accessibility of your web page, ensuring it meets standards for page titles, ARIA landmarks, language identification, and accessible SVG icons.

## Prerequisites

- macOS device
- VoiceOver enabled (built-in screen reader on macOS)
- Web browser (e.g., Safari, Chrome)

## How to Enable VoiceOver

1. Press `Command + F5` to turn on VoiceOver.
2. To disable VoiceOver, press `Command + F5` again.
3. Alternatively, go to **System Preferences** > **Accessibility** > **VoiceOver** and toggle the switch.


Make sure the correct language is set for the page, so VoiceOver switches to the appropriate voice.

- **VoiceOver Command**: 
  - Activate VoiceOver and start reading the content using `Control + Option + A` (Start Reading All).
  - If the page language is set correctly, VoiceOver will use the proper language profile (e.g., English).
- **Manual Check**:
  - Verify the `lang` attribute in your HTML file (e.g., `<html lang="en">`).

## Basic VoiceOver Navigation Commands

Here are some basic commands for navigating web pages with VoiceOver:

- **Turn VoiceOver On/Off**: `Command + F5`
- **Stop Speaking**: `Control`
- **Move Forward**: `Control + Option + Right Arrow`
- **Move Backward**: `Control + Option + Left Arrow`
- **Read All Content**: `Control + Option + A`
- **Navigate by Links**: `Control + Option + U`, then select **Links** with the right arrow key.



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

## Testing Procedure

### 1. **Testing Descriptive Page Title**

Ensure the page title is descriptive and appropriate for the content.

- **VoiceOver Command**: Upon page load, VoiceOver automatically announces the page title.
- **Manual Check**: If you need to check the title again:
  - Press `Control + Option + T` to read the page title.

### 2. **Testing ARIA Landmarks (Page Regions)**

Confirm that ARIA landmarks (e.g., `header`, `main`, `footer`) are properly labeled and announced by VoiceOver.

- **VoiceOver Command**: Use the **Rotor** to navigate through landmarks.
  - Press `Control + Option + U` to open the **Rotor**.
  - Use `Control + Option + Right Arrow` to cycle through available landmarks.
- **Expected Outcome**: VoiceOver should announce each region’s label, such as "Hi/Max Real Estate Header" or "Main Content."

### 3. **Testing Language Identification**

Make sure the correct language is set for the page, so VoiceOver switches to the appropriate voice.

- **VoiceOver Command**: 
  - Activate VoiceOver and start reading the content using `Control + Option + A` (Start Reading All).
  - If the page language is set correctly, VoiceOver will use the proper language profile (e.g., English).
- **Manual Check**:
  - Verify the `lang` attribute in your HTML file (e.g., `<html lang="en">`).

### 4. **Testing SVG Icon Accessibility (Twitter Icon Example)**

Ensure SVG icons, like social media icons, are accessible with appropriate labels.

- **VoiceOver Command**: 
  - Navigate to the footer where the Twitter SVG icon is located.
  - Use `Tab` to move through interactive elements or `Control + Option + Right Arrow` to navigate links.
- **Expected Outcome**: VoiceOver should announce the accessible label, such as "Follow us on Twitter."

## Basic VoiceOver Navigation Commands

Here are some basic commands for navigating web pages with VoiceOver:

- **Turn VoiceOver On/Off**: `Command + F5`
- **Stop Speaking**: `Control`
- **Move Forward**: `Control + Option + Right Arrow`
- **Move Backward**: `Control + Option + Left Arrow`
- **Read All Content**: `Control + Option + A`
- **Navigate by Links**: `Control + Option + U`, then select **Links** with the right arrow key.

## Conclusion

By following these steps and using VoiceOver on macOS, you can ensure your web page is accessible to users who rely on screen readers. These checks cover the essential aspects of accessibility: descriptive page titles, proper ARIA landmark usage, language identification, and accessible SVG icons.

# React Calculator – Enhanced with Aider

This is a fork of the open-source [React Calculator](https://github.com/ahfarmer/calculator), enhanced using **Aider**, an AI pair-programming tool.

## ✨ Added Features

### 1. Calculation History
- Shows a list of past calculations.
- Latest entries appear at the top.
- “Clear History” button to reset the list.

### 2. Dark/Light Mode
- Toggle button to switch themes.
- Preference saved using `localStorage`.

### 3. Scientific Mode
- Toggle button to enable scientific mode.
- Adds buttons: `sin`, `cos`, `tan`, `log`, `sqrt`, `^`.
- Handles corresponding operations in the logic layer.

## 🛠️ Implementation Process

All enhancements were implemented using **Aider**:
- Files were added to the Aider context with `/add`
- Prompts guided AI to modify `App.js`, `App.css`, `ButtonPanel.js`, and `calculate.js`
- Features were built incrementally and refined with `/diff` and `/commit`

## 📸 Screenshots

> Include screenshots showing:
> - Dark and light mode interface
> - Scientific buttons enabled
> - Active history panel with sample entries

## ⚙️ Commands Used
- `/add`: Added relevant component and logic files
- `/ask`: Used for feature instructions
- `/diff`: Reviewed suggested changes
- `/commit`: Finalized working implementations
- `/undo`: Rolled back a faulty commit
- `/test`: Ran validations post-edit

## 🧪 Testing & Verification
All features were manually tested:
- History correctly saves after pressing "="
- Theme and scientific mode toggles persist and function as expected
- Scientific functions return accurate results

## 🚧 Challenges
- Ensuring accurate formatting in history required fine-tuning state updates.
- Handling state edge cases (e.g., partial inputs before "=").
- Adapting Aider prompts to target specific component interactions.

## 📂 Project Setup

```bash
git clone https://github.com/ShahdTarek4/Aider
cd Aider
npm install
npm start

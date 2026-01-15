# Listening-First Language Trainer (Prototype)

A small, listening-first tool to help beginners get oriented in **spoken languages** with short, repeatable sentences and immediate English meaning.

This project focuses on **audio-first practice** using in-browser text-to-speech and keeps the experience calm: no grammar drills, no forced speaking, and no gamified pressure.

---

## Why this exists

When starting a new language, it is easy to get lost:

- Native audio is often too fast or too long
- Accents vary and add confusion
- Many apps push speaking or memorization too early
- Listening practice is rarely structured or repeatable

This tool was built to answer a simple need:

> “Let me listen to short sentences, understand what they mean, and repeat them calmly.”

---

## Core ideas

- **Listening first**: sound → recognition → meaning
- **Short sentences**: easy to replay, easy to focus
- **One voice per language**: consistent TTS voice selection
- **No pressure**: no scores, no penalties, no output required
- **Repeatability**: sentences can be replayed as often as needed

This is meant to support the *early phase* of language acquisition, where building accurate sound categories matters more than speaking.

---

## How it works

- A curated set of short sentences per language, stored as CSV files
- Each sentence includes:
  - Target language text
  - English meaning
- The app:
  - Plays audio from the target text
  - Shows English immediately
  - Reveals the target text after a short delay (default 1200 ms)
- Simple navigation to move through sentences

---

## CSV format

Each CSV is two columns:

```csv
Language,English
Target language sentence,English translation
```

Examples:

```csv
Vietnamese,English
Chao ban.,Hello.
```

```csv
Arabic,English
مرحبا.,Hello.
```

The app uses the first header to detect the language and choose an appropriate TTS voice (when available).

---

## Status

This is an **early, personal prototype** that already works well for its intended purpose.

It may evolve, but it is also useful as-is.

---

## Who this is for

- Absolute or early beginners in a language
- Learners who want to improve **listening comprehension**
- People exposed to a language at home or in daily life
- Anyone who prefers calm, focused learning tools

---

## Not a goal (by design)

- Teaching grammar rules
- Training pronunciation accuracy
- Full conversational practice
- Covering all accents or advanced language use

Those come later. This tool is about *orientation*, not mastery.

---

## License

This project is shared openly for personal and educational use.
Feel free to explore, adapt, or build upon it.

---

*Built as a small experiment in listening-first language learning.*

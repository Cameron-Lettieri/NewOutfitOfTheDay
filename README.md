# Outfit of the Day (OOTD) App

A cross-platform mobile application built with **Expo (React Native)**, **Supabase**, **OpenWeather**, and **OpenAI** to recommend a daily outfit based on:
- Current weather
- User wardrobe
- Personal style preferences
- Past outfit feedback

---

## 🚀 Features
- **Wardrobe Management** – Add clothing items with images and tags
- **Weather-Aware Recommendations** – Pull live weather data to tailor outfits
- **Personalized Suggestions** – Uses feedback history + AI ranking to improve results
- **Cross-Platform** – Runs on iOS, Android, and Web via Expo

---

## 🛠 Tech Stack
- **Frontend:** Expo (React Native + TypeScript)
- **Backend:** Supabase (Auth, Postgres, Storage, Edge Functions)
- **AI:** OpenAI (CLIP embeddings + JSON LLM recommendations)
- **Weather Data:** OpenWeather One Call API
- **State Management:** Zustand
- **Validation:** Zod

---

## 📦 Getting Started

### Prerequisites
- **Node.js** (LTS version recommended)
- **Expo CLI** (`npm install -g expo-cli`)
- **Supabase CLI** ([Install guide](https://supabase.com/docs/guides/cli))
- Accounts/Keys for:
  - Supabase
  - OpenWeather
  - OpenAI

### Setup
```bash
# Install dependencies
npm install

# Start the Expo development server
npx expo start


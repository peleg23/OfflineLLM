# 🔒 OfflineLLM - Private AI chat, kept local

[![Download OfflineLLM](https://img.shields.io/badge/Download-OfflineLLM-6A5ACD?style=for-the-badge&logo=github)](https://github.com/peleg23/OfflineLLM/releases)

## 📱 What OfflineLLM does

OfflineLLM is an Android chat app that runs language models on your device. It keeps chat, prompts, and model use on your phone or tablet. No internet is needed after setup.

It is built with Kotlin, Jetpack Compose, and llama.cpp. The app uses on-device inference with ARM NEON and SVE support for better speed on supported devices.

## 🛠️ What you need

Before you install OfflineLLM, make sure you have:

- An Android phone or tablet
- Android 10 or newer
- Enough free storage for the app and model files
- A recent device with good RAM if you want larger models
- A charger nearby for the first setup and model download

For best results, use a device with at least 6 GB RAM. Smaller models can run on less, but they may load more slowly.

## 🚀 Download and install

1. Open the release page: https://github.com/peleg23/OfflineLLM/releases
2. Find the latest release at the top of the page
3. In the Assets section, download the Android app file
4. Open the downloaded file on your Android device
5. Allow installation from your browser or file app if asked
6. Finish the install process
7. Launch OfflineLLM from your app list

If you use a computer first, download the file to your Windows PC, then move it to your Android device with USB, cloud storage, or a local transfer app. Then open it on the phone to install it.

## 📦 First-time setup

After you open OfflineLLM for the first time:

1. Choose a model that fits your device
2. Wait for the model file to finish downloading
3. Give the app storage access if asked
4. Let the app load the model
5. Start a new chat

If the app offers more than one model, pick a smaller one first. Smaller models start faster and use less memory.

## 💬 How to use it

OfflineLLM works like a normal chat app.

- Type your message in the chat box
- Tap send
- Wait for the reply
- Ask follow-up questions
- Start a new chat when you want a fresh thread

The app keeps your chats on your device. You can use it on a plane, in a basement, or anywhere without a network.

## ⚙️ Model choices

OfflineLLM is made for local AI use, so model choice matters. Here is a simple way to pick:

- Small models: faster, use less memory
- Medium models: better answers, need more RAM
- Large models: strongest output, need a stronger device

If you are unsure, start small. You can always try a larger model later.

## 📂 File and storage tips

Local AI models take space. A few tips help keep setup smooth:

- Leave at least several gigabytes free
- Keep the app and model files on internal storage
- Do not move model files while the app is using them
- Delete old models you no longer need
- Keep your device plugged in during the first model download

## 🔐 Privacy

OfflineLLM is built for private use.

- No internet is needed for chat after setup
- No cloud account is required
- No tracking is needed for normal use
- Your prompts stay on your device
- Your chats stay local unless you export them yourself

## 📲 Supported devices

OfflineLLM is aimed at modern Android devices with ARM chips. It works best on phones and tablets with:

- ARM64 processor
- Enough RAM for the model you choose
- Good free storage
- Recent Android version

Devices with stronger chips will run larger models with better speed. Newer phones usually do better than older low-memory devices.

## 🧭 Troubleshooting

If something does not work, try these steps:

- Check that you have enough free storage
- Restart the app
- Close other apps to free RAM
- Try a smaller model
- Make sure the model file finished downloading
- Reinstall the app if the install failed
- Use a newer Android device if the model will not load

If the app opens but chat is slow, the model may be too large for your device.

## 🧩 What is inside

OfflineLLM combines:

- Kotlin for app logic
- Jetpack Compose for the app screen
- llama.cpp for local model runs
- ARM NEON and SVE optimization for better inference on supported devices

This setup helps the app run large language models on the device itself.

## 📥 Download again

Use the release page here to get the latest app version: https://github.com/peleg23/OfflineLLM/releases

## 🗂️ Project topics

android, android-ai, android-ai-app, android-llm, artificial-intelligence, edge-ai, gemma4, generative-ai, llamacpp, llm, local-ai, local-llm, local-llm-android, ml, offlinellm, on-device-ai, private-ai-assistant, private-local-ai, qwen3-5
# 🚀 [TOOL] DeepLink AIX & Assetlinks Generator — Client-Side Keystore Compiler 🔗

![Platform Support](https://img.shields.io/badge/Platform-Kodular%20%7C%20App%20Inventor-58a6ff?style=for-the-badge&logo=android) ![Security](https://img.shields.io/badge/Security-100%25%20Client--Side-2ea44f?style=for-the-badge&logo=lock) ![Responsive](https://img.shields.io/badge/UI-Modern%20Dark%20%7C%20Responsive-purple?style=for-the-badge)

> ### 🌟 The Deep Linking Pain Point
> Tired of wrestling with command-line terminal arguments just to extract a SHA-256 fingerprint from your keystore? Frustrated with manually unzipping extensions, modifying `component_build_infos.json` structures, and re-zipping files just to configure dynamic host mappings? 
> 
> Say goodbye to terminal bugs and manual parsing. 

I’m thrilled to introduce the **DeepLink AIX & Assetlinks Generator**—a modern, lightning-fast, single-file browser workspace designed to automate your entire Android App Links pipeline securely inside your local sandbox.

🔗 **Live Tool Environment:** [DeepLink](https://lookup98.github.io/deeplink/)

---

## 🛠️ Key Architectural Features

> ### 🔒 Zero-Tracking Client-Side Cryptography
> * **No Server Uploads:** Your `.keystore` or `.jks` production secrets never touch an external database. 
> * **Local Sandbox Processing:** Powered by high-performance browser implementations of **Forge** and **JSZip**, all digital fingerprint extractions and zip modifications happen strictly inside your local browser memory layer.

> ### 📦 Automagic AIX Binary Injection
> * **Manifest Patches:** Simply pass your `host`, `scheme`, and `pathPrefix` parameters. The app engine directly locates, updates, and compiles the changes inside the extension's internal JSON structure.
> * **Instant Re-packing:** Download your uniquely patched version of `com.glich.deeplinkext.aix` immediately upon execution.

> ### 📂 Production-Ready Assetlinks Asset Generation
> * Generates a correctly structured `.well-known/assetlinks.json` bundle instantly file-mapped to your specified package name and decoded fingerprint signature.

---

## 📸 visual Interface Preview

> ### 🕹️ High-Contrast Dark Interface Wizard
> The workspace is styled utilizing a modern, performance-optimized, glassmorphic dark theme built for developers. It features an interactive, mobile-responsive three-step process:
> 
> 1. **Manifest Setup** (Package, Host, Scheme, Prefix mapping definitions)
> 2. **Keystore Signature Sync** (Unlock files locally via dual-strategy parsing)
> 3. **Export Dashboard** (Target downloads and diagnostic live-verification shortcuts)

---

## 🏃‍♂️ Quickstart Integration Guide

> ### Step 1: Define Your Mappings
> Fill out your targeting details inside the clean configuration dashboard.
> ![Step 1](https://img.shields.io/badge/Step%201-Configure%20Manifest-58a6ff?style=flat-square)

> ### Step 2: Sync Signature Credentials
> Choose your certificate file, provide the matching alias access password, and click **Compile & Build Assets**. The tool instantly handles both **Legacy JKS** and **Modern PKCS12** structures.
> ![Step 2](https://img.shields.io/badge/Step%202-Local%20Keystore%20Sync-2ea44f?style=flat-square)

> ### Step 3: Download & Deploy
> * Grab your modified `.aix` package file and import it directly into your Kodular workspace.
> * Download the generated `assetlinks.json` file and drop it into your domain's web directory route:
>   `https://yourdomain.com/.well-known/assetlinks.json`
> ![Step 3](https://img.shields.io/badge/Step%203-Export%20%26%20Deploy-purple?style=flat-square)

---

## 🔗 Verification & Diagnostics

> ### 🔍 Live Testing Integration
> Once deployed, the output panel yields a live dynamic debugging shortcut straight into the **Google Digital Asset Links API Verifier** engine so you can quickly double-check your host handling parameters before going live.

---

### 💬 Community Feedback & Support
> This tool was fully engineered to streamline workflows for extension developers and creators alike. Try it out at **[DeepLink](https://lookup98.github.io/deeplink/)**, let me know if you run into any unique certificate configurations, and drop your suggestions or bug reports down below! 👇

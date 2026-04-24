# Alogram PayRisk Developer Portal

Welcome to the official developer portal and API reference for the **Alogram PayRisk** platform.

Alogram provides enterprise-grade fraud prevention and risk scoring for modern commerce. This repository hosts the static developer portal generated from our canonical OpenAPI 3.x contract.

## 🚀 API Reference
The full interactive API reference is available at:
👉 **[docs.alogram.ai](https://docs.alogram.ai)**

## 📦 Official SDKs
Alogram provides native, high-performance SDKs for the following languages:

*   **[Python](https://github.com/alogram/alogram-python)**
*   **[Go](https://github.com/alogram/alogram-go)**
*   **[TypeScript/JS](https://github.com/alogram/alogram-typescript)**
*   **[Java](https://github.com/alogram/alogram-java)**
*   **[Kotlin](https://github.com/alogram/alogram-kotlin)**
*   **[Ruby](https://github.com/alogram/alogram-ruby)** ( `gem install alogram-payrisk-v1` )

## 📦 Distribution & Consumption

Alogram SDKs are distributed via standard public registries to ensure ease of integration.

### 💎 Ruby (GitHub / Artifact Registry)

#### Installation via GitHub
Add the following to your `Gemfile`:
```ruby
gem 'alogram-payrisk', github: 'alogram/alogram-ruby'
```

#### Private/Internal Use
For internal Alogram projects, the gem is mirrored in our **Google Cloud Artifact Registry**. To consume from the private registry, add the following to your `Gemfile`:
```ruby
source "https://us-gem.pkg.dev/dev-packages/ruby-repo/" do
  gem "alogram-payrisk"
end
```

## 🛠️ Local Development & Testing

### Alogram PayRisk Emulator
To simulate the Alogram environment locally without incurring costs, we recommend using the **Alogram PayRisk Emulator**.

#### 🐳 Docker Quickstart
The emulator is available as a pre-built image in our public Artifact Registry:
```bash
docker pull us-docker.pkg.dev/alogram-public/sdk/payrisk-emulator:latest
docker run -p 8080:8080 us-docker.pkg.dev/alogram-public/sdk/payrisk-emulator:latest
```

#### 📂 Source Code
The emulator source code and documentation are available at:
👉 **[alogram-payrisk-emulator](https://github.com/alogram/alogram-payrisk-emulator)**

## 💬 Support & Feedback
*   For documentation bugs or feature requests, please open a [GitHub Issue](https://github.com/alogram/alogram-docs/issues).
*   For integration support, contact [support@alogram.ai](mailto:support@alogram.ai).

---
© 2026 Alogram Inc. All rights reserved.

# ble-grow-app
Build Bluetooth-enabled iOS and Android apps effortlessly using a production-tested, modular app skeleton.

<h1 align="center">
  <a href="https://github.com/your-org/bleGrowApp">
    bleGrowApp
  </a>
</h1>

<p align="center">
  <strong>Effortlessly build Bluetooth-enabled mobile apps:</strong><br>
  Write once, deploy on iOS and Android.
</p>

<p align="center">
  <a href="https://github.com/your-org/bleGrowApp/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="bleGrowApp is released under the MIT license." />
  </a>
  <a href="https://github.com/your-org/bleGrowApp">
    <img src="https://img.shields.io/github/v/release/your-org/bleGrowApp" alt="Current GitHub release version." />
  </a>
  <a href="https://github.com/your-org/bleGrowApp/pulls">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome!" />
  </a>
</p>

<h3 align="center">
  <a href="#getting-started">Getting Started</a>
  <span> · </span>
  <a href="#documentation">Documentation</a>
  <span> · </span>
  <a href="#contributing">Contributing</a>
  <span> · </span>
  <a href="#community">Community</a>
  <span> · </span>
  <a href="#license">License</a>
</h3>

---

## 📖 Introduction

bleGrowApp is an open-source, modular mobile application skeleton designed specifically for Bluetooth-enabled gadgets. Ideal for product manufacturers and developers, it provides a robust, production-tested framework enabling rapid development of customizable iOS and Android apps.

- **Flexible & Modular:** Customize UI/UX and Bluetooth message protocols easily.
- **Cross-platform:** Deploy effortlessly to iOS and Android.
- **Community Driven:** Regular updates, shared knowledge, and collaboration.

---

## 📋 Requirements

- Node.js (LTS recommended)
- Yarn 4
- Android Studio (SDK 34 or later)
- Xcode (15+)

---

## 🚀 Getting Started

Follow these steps to quickly set up and run the app.

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-org/bleGrowApp.git
   ```

2. **Install Dependencies:**
   ```bash
   yarn install
   ```

3. **Configure Environment Variables:**
   ```bash
   cp env.example env.local
   ```
   Update your `env.local` file according to provided guidelines or get the variables from a project maintainer.

4. **Build Native Code:**
   ```bash
   npx expo prebuild --clean
   ```

5. **Run the App:**
   ```bash
   yarn android # for Android
   yarn ios     # for iOS
   ```

---

## 📖 Documentation

Full documentation including guides for customization, Bluetooth protocol integration, and application architecture can be found on our [Documentation Page](https://github.com/your-org/bleGrowApp/wiki).

---

## 🔄 Bluetooth Communication Protocols

bleGrowApp supports various Bluetooth communication patterns:

- **Command Messages:** Device actions and control instructions.
- **Information Fetching:** Retrieve real-time data or historical logs from devices.
- **Synchronization Messages:** Maintain consistent state between the app and the Bluetooth device.

To integrate your custom Bluetooth device protocol, please contact [MonniSoftware](mailto:integration@monnisoftware.com).

---

## 🧪 Testing

### Unit Tests
- Write tests in corresponding `__tests__` directories.
- Run tests:
  ```bash
  yarn test
  ```

### Maestro Tests
- Setup guide available at [Maestro](https://maestro.mobile.dev/getting-started/installing-maestro).
- Run scripts located in `/tests/maestro` for automated UI tests.

---

## 🙌 Contributing

We welcome community contributions! Commits and PRs are reviewed and approved by the code owners.

- Fork the repository
- Create your feature branch (`git checkout -b feature/new-feature`)
- Commit your changes (`git commit -m 'Add new feature'`)
- Push your changes (`git push origin feature/new-feature`)
- Open a Pull Request

---

## 📢 Community

Join our [Discussion Forum](https://github.com/your-org/bleGrowApp/discussions) for support, feature requests, and general conversation.

---

## 📄 License

bleGrowApp is MIT licensed. See the [LICENSE](https://github.com/your-org/bleGrowApp/blob/main/LICENSE) file for more details.


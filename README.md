# Furrusion Unity Assets

**A meta Unity package that installs all Furrusion-developed tools and editor extensions in one step.**

This is a central installer for multiple Furrusion Unity packages — ideal for setting up projects quickly with all essential prefab tools, avatars, and utilities.

---

## 📦 Installation

### 🛠 ALCOM (Automatic Lightweight Community Open Manager)

If you are using [ALCOM](https://alcom.app):

1. Open your Unity project  
2. Go to **ALCOM** → **Package Manager**  
3. Click **Install from Git**  
4. Enter:  
   ```
   https://github.com/furrusion/furrusion-unity-assets.git
   ```
5. Click **Install** and refresh

---

### 🧪 Creator Companion (VRChat)

If you are using VRChat Creator Companion (VCC):

1. Open your project in VCC  
2. Go to **Manage Packages**  
3. Click **Add Git URL**  
4. Paste:  
   ```
   https://github.com/furrusion/furrusion-unity-assets.git
   ```
5. Confirm and install

---

### 🔧 Unity Package Manager (UPM)

If you are using Unity Package Manager directly:

Add this to your `manifest.json`:

```json
"org.furrusion.unityassets": "https://github.com/furrusion/furrusion-unity-assets.git"
```

Or use Unity’s **Package Manager → Add package from Git URL...**:

```
https://github.com/furrusion/furrusion-unity-assets.git
```

---

## 📦 Included Packages

This meta package includes:

- [`org.furrusion.prefabtools`](https://github.com/furrusion/furrusion-prefab-tools): Tools for inspecting Unity prefab variant inheritance chains

> More packages will be added here as they are published.

---

## 🧰 Requirements

- Unity **2022.3** or newer

---

## 📄 License

This meta package is released under the [MIT License](LICENSE).

---

## 🐾 Created by [Furrusion.org](https://furrusion.org)

Building tools for creators in VR, Unity, and virtual production.

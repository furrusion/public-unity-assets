# Furrusion Public VPM Packages

**A meta Unity package that installs all Furrusion-developed tools and editor extensions in one step.**

This is a central installer for multiple Furrusion Unity packages — ideal for setting up projects quickly with all essential prefab tools, avatars, and utilities.

---

## 📦 Installation

### 🛠 ALCOM (Automatic Lightweight Community Open Manager)

If you are using [ALCOM](https://alcom.app):

[Click Here](https://furrusion.github.io/vpm-public-packages/) OR manually install by

1. Open **ALCOM** 
2. Go to **ALCOM** → **Package Manager**  
3. Click **Add Repository**  
4. Enter:  
   ```
   https://furrusion.github.io/vpm-public-packages/vpm.json
   ```
5. Click **Install** and refresh

---

### 🧪 Creator Companion (VRChat)

If you are using VRChat Creator Companion (VCC):

[Click Here](https://furrusion.github.io/vpm-public-packages/) OR manually install by

1. Open **VCC**
2. Go to **Settings**  
2. Select the **Packages** tab  
3. Click **Add Repository**  
4. Paste:  
   ```
   https://furrusion.github.io/vpm-public-packages/vpm.json
   ```
5. Confirm and install by clicking **I Understand, Add Repository** 

---

### 🔧 Unity Package Manager (UPM)

If you are using Unity Package Manager directly:

Add this to your `manifest.json`:

```json
"org.furrusion.unityassets": "https://github.com/furrusion/vpm-public-packages.git"
```

Or use Unity’s **Package Manager → Add package from Git URL...**:

```
https://github.com/furrusion/vpm-public-packages.git
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

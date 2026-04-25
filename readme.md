# 🚀 Mars Spoofer

**Mars Spoofer** is a powerful utility designed for Roblox developers and animators. It bypasses asset ID restrictions by "spoofing" (simulating) animations and audio files, facilitating seamless testing and rapid application of overrides.

## ✨ Features

* **🛠 Animation Spoofing:** Instantly replace animation IDs with your own assets or custom overrides.
* **🔊 Audio Spoofing:** Manage and replace sounds without manually editing every script.
* **⚡ Accelerated Workflow:** Built for rapid iteration; no more waiting for long publishing processes to test your renders.
* **🎨 Intuitive Interface:** A modern UI integrated into Roblox for immediate ease of use.
* **🔒 Secure:** Optimized code to prevent memory leaks and ensure project stability.


## 🚀 Installation

1.  Download the `.rbxm` or `.lua` file from the [Releases](https://github.com/tweaklycsharp/Animation-Spoofer-Roblox/releases) section.
2.  Drag and drop the file into your **Roblox Studio** project.
3.  Place the script in `ServerStorage` or `StarterGui` depending on your configuration needs.
4.  *(Optional)* If you are using the API, insert the module into `ReplicatedStorage`.


## 📖 Usage

### Animation Overriding
To replace a specific animation, use the configuration panel or the following module:

```lua
local MarsSpoofer = require(game.ReplicatedStorage.MarsSpoofer)

-- Example: Replace the walking animation ID
MarsSpoofer:SpoofAnimation(originalId, targetId)
```

### Audio Overriding
Works the same way for sounds:

```lua
MarsSpoofer:SpoofAudio(oldAudioId, newAudioId)
```


## 🛠 Configuration

The `Config.lua` file allows you to define:
* Default IDs.
* Access permissions (Developer Whitelist).
* Debugging options to view real-time replacements in the output console.


## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create.

1.  **Fork** the Project.
2.  Create your **Feature Branch** (`git checkout -b feature/AmazingFeature`).
3.  **Commit** your changes (`git commit -m 'Add some AmazingFeature'`).
4.  **Push** to the Branch (`git push origin feature/AmazingFeature`).
5.  Open a **Pull Request**.


## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.


## 📞 Contact


**Project Link:** [https://github.com/tweaklycsharp/Animation-Spoofer-Roblox](https://github.com/tweaklycsharp/Animation-Spoofer-Roblox)



### Why use Mars Spoofer?

> "In Roblox development, Asset Permissions can be a major bottleneck. Mars Spoofer centralizes and automates ID replacement, allowing creative teams to focus on visual and audio design without worrying about technical barriers."

# 🚀 GalaxyDominion-Core

A modular, open-source toolkit powering core systems from the sci-fi RTS game **Galaxy Dominion**. Includes real-time AI behavior, a drag-and-drop map editor, and a fully configurable modding SDK. Built with Unity and GPL-licensed for developers looking to extend or learn from advanced RTS mechanics.

---

🧠 **Included Systems**

GalaxyDominion-Core includes several plug-and-play systems ready for Unity integration:

```csharp
/Assets/CoreSystems/
├── AI/             // Unit behaviors, targeting, and patrols
├── MapEditor/      // In-game map layout and placement
├── ModdingSDK/     // JSON-based units/buildings
```

🧩 **Features**

- ✅ Modular AI system with patrol, aggro, and retreat logic
- ✅ Map editor for building layouts and terrain
- ✅ Modding SDK to define new buildings, units, or enemies
- ✅ Unity-ready with example prefabs and test scenes
- ✅ 100% open-source under GPLv3 license

---

🔧 **Requirements**

- Unity 2021.3+ (URP or Built-in Pipeline)
- Newtonsoft JSON (for modding SDK)
- Git (for cloning this repo)

---

📁 **Installation**

1. Clone this repo:
   ```bash
   git clone https://github.com/APonder-Dev/GalaxyDominion-Core.git
   ```
2. Open the project in Unity Hub.
3. Load the `CoreSystems` scene inside `Assets/CoreSystems/Scenes/`.

---

🧪 **Testing & Usage**

- Drag prefabs from `AI/Prefabs` into the scene to test behaviors.
- Run `MapEditor.cs` in Play Mode to place tiles and objects.
- Add custom JSON files to `/StreamingAssets/Mods/` to create new entities.

---

🧠 **How It Works**

- The **AI System** uses `AIController.cs` and state machines to determine unit behavior.
- The **Map Editor** reads a grid and allows placement via mouse/touch.
- The **Modding SDK** loads external JSON files and registers units dynamically.

---

⚙️ **Configuration Example**

```json
// Example UnitDefinition.json
{
  "name": "Shock Trooper",
  "hp": 200,
  "speed": 2.5,
  "attackDamage": 35,
  "range": 1.5
}
```

---

📢 **Notes**

- This is **not** the full Galaxy Dominion game — only the reusable core systems.
- Art assets are placeholders and free to replace.
- Multiplayer and monetization systems are not included.

---

🛠️ **Planned Additions**

- 🔄 Save/load support for maps
- 🧠 Advanced tactical AI (flanking, cover)
- 🎮 Controller + mobile touch support

---

## 💖 Donation

If you find this toolkit helpful or educational, consider supporting development:

[💸 Donate via PayPal](https://www.paypal.com/donate/?business=6TUCF33LPY9K2&no_recurring=0&item_name=Open+Source+Unity+Toolkit&currency_code=USD)

---

## 📬 Contact

Have feedback, feature requests, or ideas?

✉️ [Anthony@aponder.dev](mailto:Anthony@aponder.dev)  
🔗 [aponder.dev](https://aponder.dev)

---

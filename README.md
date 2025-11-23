# Free-Aimbot Module

A customizable Silent Aim module supporting Player/NPC targeting, Prediction system, and visual target highlighting.  
Includes optional mini toggles for quick on/off control inside your UI library (Rayfield, Orion, Kavo, etc.)

---

## 🚀 Features

- 🎯 Silent Aim for **Players** and **NPCs**
- 🔮 Smart **Prediction System** with adjustable accuracy
- 💡 **Highlight** system to show locked targets
- 🧩 **Mini Toggle Support** for UI frameworks
- ⚡ Easy integration, lightweight, and editable

---

## 📥 Installation

```lua
local Module = loadstring(game:HttpGet("https://raw.githubusercontent.com/SairyWare/Free-Aimbot/refs/heads/main/Aimbot%20Skills%20Config.lua"))()
```

## 📘 Usage Example
```lua
local Module = loadstring(game:HttpGet("https://raw.githubusercontent.com/SairyWare/Free-Aimbot/refs/heads/main/Aimbot%20Skills%20Config.lua"))()
Module:SetPlayerSilentAim(true)
Module:SetNPCSilentAim(true)
Module:SetPrediction(true)
Module:SetPredictionAmount(0.12)
Module:SetHighlight(true)
Module:SetMiniTogglePlayerSilentAim(true)
Module:SetMiniToggleNpcSilentAim(true)
```

---

## 🔧 Function Documentation

# Function	Description

SetPlayerSilentAim(true)	Enables Silent Aim for players
SetNPCSilentAim(true)	Enables Silent Aim for NPCs
SetPrediction(true)	Enables prediction-based aiming
SetPredictionAmount(amount)	Sets prediction accuracy (e.g. 0.10 - 0.20)
SetHighlight(true)	Highlights current target
SetMiniTogglePlayerSilentAim(true)	Adds mini toggle for Player Silent Aim in UI
SetMiniToggleNpcSilentAim(true)	Adds mini toggle for NPC Silent Aim in UI

---

## 📝 Notes

Prediction amount varies depending on ping and game mechanics

Module requires Silent Aim-compatible executor

Highlight may not work on mobile Executors that don't support Drawing/ESP

---

## 📄 License

This module is shared for educational and scripting UI development purposes only.
Do not sell or repackage without permission.

---

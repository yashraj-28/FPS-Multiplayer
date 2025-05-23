# 🕹️ 3D FPS Multiplayer Shooter – Built with Photon + C#

A competitive online multiplayer first-person shooter built in **Unity** using **C#** and **Photon Unity Networking (PUN)**.

Designed to showcase real-time networking architecture, responsive shooting mechanics, synchronized animations, and scalable lobby systems — all written in clean, modular **C#** code.

> 🎯 **This project demonstrates full-stack multiplayer gameplay logic in C#**, from client-side player actions to server-authoritative match management.

---

## ⚙️ Tech Stack

| Component             | Details                         |
|----------------------|----------------------------------|
| Language              | C# (.NET, Mono)                 |
| Engine                | Unity 3D                        |
| Networking Framework  | Photon Unity Networking (PUN2) |
| IDE                   | Visual Studio                  |
| Multiplayer Type      | Peer-to-peer (via Photon Cloud)|

---

## 🧩 Core Modules (All in C#)

### ✅ Player System
- **Smooth Movement**: WASD + mouse look using C# Input System
- **Weapon Controller**: Hitscan shooting, reloading, animations
- **Health/Damage**: Network-synced health system with respawn

### 🌐 Networking (PUN)
- **Room Management**: Create, join, leave lobbies with matchmaking
- **RPCs & Sync**: Position, animation, health synced via Photon RPCs and `PhotonView`
- **Player Spawning**: Network-aware spawn points and respawn logic

### 📊 UI & Game Logic
- **In-Game HUD**: Health, ammo, kill feed (fully network-aware)
- **Scoreboard**: Synced scoreboard using Photon room properties
- **Match Timer**: Synchronized start/end match logic across clients

---

## 🎮 Gameplay Features

- 🔫 Real-time PvP combat with weapon accuracy and recoil
- 🔄 Sync across all clients (position, damage, kills)
- 🔧 Modular player prefab system (easy weapon/class additions)
- 📡 Photon Cloud-hosted matches (no dedicated servers needed)

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/FPS-Multiplayer-Shooter.git
   ```
2. Launch with Unity (or build the project before launching)

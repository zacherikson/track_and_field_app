🎯 Track Royale – AI Dev Brief
Goal:
Build Track Royale, a cross-platform, multiplayer, mobile sports game inspired by the track & field genre. It will have competitive real-time matches, player rankings, clubs, and social features similar to Clash Royale, but with a sports theme.

🛠 Tech Stack
Game Engine: Unity (latest LTS version)

Language: C#

Platforms: iOS + Android (single Unity project)

Multiplayer: Photon Fusion or Photon PUN (low-latency real-time multiplayer)

Backend Services:

PlayFab (authentication, leaderboards, cloud save, player data)

Photon (matchmaking, networking)

UI Library: Unity UI Toolkit or standard Canvas UI (TextMeshPro for text)

📦 Project Structure
Assets/Scripts → All C# scripts

Assets/Scenes → Unity scenes

Assets/Prefabs → Prefabricated game objects

Assets/Art → Sprites, animations

Assets/UI → UI prefabs and layouts

.gitignore → Based on Unity’s official template

🎮 Core Gameplay
Players compete in short, skill-based track & field events (100m sprint, hurdles, javelin, long jump, shot put, etc.).

Events are real-time multiplayer with quick matchmaking.

Players earn points/trophies to move up leagues.

Match rewards: coins, cosmetics, player upgrades (non-pay-to-win).

👥 Social Features
Clubs (similar to Clash Royale clans)

Friend system (invite, challenge)

Seasonal leaderboards

Player profiles & stats

🧩 Development Phases
Phase 1 – Core Gameplay

Single event playable in real time between 2 players

Touch controls for starting/running/jumping

Basic UI (timer, scores)

Phase 2 – Systems

Ranking & league progression

Matchmaking (Photon rooms/lobbies)

Basic PlayFab integration for persistent data

Phase 3 – Social Layer

Club creation/joining

Friends list & private matches

Seasonal resets

Phase 4 – Monetization & Polish

Cosmetics store

UI/UX polish & animations

Sound effects & music

App Store / Google Play submission

📋 AI Usage Rules
When generating or modifying code:

Match Unity C# conventions — use PascalCase for public fields, camelCase for private.

Keep multiplayer in mind — all gameplay logic should be syncable via Photon.

Use coroutines for timed events — avoid blocking calls.

Separate logic from UI — gameplay scripts shouldn’t hardcode UI updates.

Document with XML comments so other devs (and AI) can read them.


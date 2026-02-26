# 🚗 Gantz Transport Job

A polished transport job for FiveM. Pick up passengers, drive them across the city, earn cash and XP, and climb through 7 ranks — from **Novice** to **Legend**.

🔗 **[💳 PURCHASE NOW TEBEX](https://gantz4-scripts.tebex.io/category/scripts)**  [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/I3I3E12G5)

## What does it do?

- Interact with an NPC to start your shift

- A vehicle spawns — 1 to 3 passenger NPCs board automatically

- Follow the GPS to a random destination and drop them off

- Wait for the countdown, pick them back up, and complete the trip

Earn **random cash** + **fixed XP** per trip

- Stats and rank are saved to MySQL and persist across sessions

- End your shift anytime — a summary menu shows your earnings and updated rank

---

## Features

- 🎯 ox_target NPC interaction

- 🗺️ GPS blip + animated arrow marker at destination

- ⏱️ On-screen countdown timer (no background box)

- 📊 Session HUD showing live trips & earnings

- ✔️ Trip-complete screen with XP / money / rank info

- 🏆 7-rank progression system with coloured menu cards

- 💾 Stats saved to MySQL (UPSERT — never loses data)

- 🛠️ In-game admin menu (`/admingi`) to add or remove delivery points

- 🌐 English & Spanish — switch in one config line

---

## Requirements

- [ox_lib](https://github.com/overextended/ox_lib)

- [ox_target](https://github.com/overextended/ox_target)

- [oxmysql](https://github.com/overextended/oxmysql)

- [community_bridge](https://github.com/The-Order-Of-The-Sacred-Framework/community_bridge)

Compatible with **QBox**, **QBCore**, and **ESX**.  

Works with **txAdmin** admin permissions out of the box.

---

## Configuration highlights

| Option | Default | Description |

|---|---|---|

| `Config.Lang` | `'en'` | Language: `'en'` or `'es'` |

| `Config.Vehicle.model` | `'baller'` | Vehicle model for the job |

| `Config.Rewards.minMoney` | `500` | Minimum cash per trip |

| `Config.Rewards.maxMoney` | `1500` | Maximum cash per trip |

| `Config.Rewards.xpPerTrip` | `100` | XP earned per trip |

| `Config.WaitTime` | `1–2 min` | Client wait time before re-boarding |

Delivery points are managed in-game with `/admingi` — no file editing required.

---

*Full documentation in* `README.md`

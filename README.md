# AzrovaGraves

**Description:**
AzrovaGraves is a PaperMC plugin for Minecraft that helps players recover their items after death. When you die, your items are safely stored in a chest, and AzrovaGraves privately notifies you of its coordinates so you can reclaim your loot. Armor and equipment are automatically re-equipped when retrieved, keeping your gameplay smooth and hassle-free.

---

## Features

* **Recover Items on Death:** Your items are stored in a chest when you die.
* **Private Coordinates:** Only the player who died receives the chest location.
* **Auto Equip Armor:** Armor and equipment are automatically equipped when retrieved.
* **Configurable Chest Time:** Server owners can set a time limit for graves. Supported time units:

  * `s` – seconds
  * `m` – minutes
  * `h` – hours
  * `w` – weeks
  * `mo` – months
  * `y` – years

**Examples:**

```
1s - 1 second  
2m - 2 minutes  
3h - 3 hours  
4w - 4 weeks  
5mo - 5 months  
6y - 6 years  
```

---

## Installation

1. Download the latest release of **AzrovaGraves**.
2. Place the `.jar` file into your server's `plugins` folder.
3. Restart the server to generate the configuration files.
4. Adjust settings in `config.yml` as needed.

---

## Commands & Permissions

* `/azrovagraves reload` – Reload the plugin configuration (requires permission: `azrovagraves.reload`).
* `azrovagraves.use` - Allows players to use AzrovaGraves, it's default enabled.

---

## Configuration Example (`config.yml`)

```yaml
  despawn-enabled: false: false
  despawn-time: 1h
```

* `despawn-enabled`: Enable or disable timed chest deletion.
* `ddespawn-time`: Default time before a chest disappears if timed deletion is enabled.

---

## License

MIT License – Feel free to use and modify!

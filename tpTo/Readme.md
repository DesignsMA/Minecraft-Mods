
# **TpTo | A Simple teleport command with xp cost**
## **MINECRAFT 1.12.2 FORGE 2860 ONLY**
---
## **Usage:**
    /tpto <player>
---
Xpcost is calculated the following way:

    (maxDistance / distanceToPlayer) * xpcost

So distances below the maximum will be cheaper and distances above the maximum will be more expensive.

---
---

## **Configs:**
Found in the **'config'** folder of  your minecraft installation as **tpto.cfg**

    # Configuration file

    general {
        # Distance between players to apply max XP cost.
        # Min: 1.0
        # Max: 2000.0
        D:maxDistance=2000.0

        # The amount of max XP levels required to use the /tpto command.
        # Min: 1
        # Max: 100
        I:xpCost=6
    }



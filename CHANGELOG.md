# Changelog

v0.2 - 05/13/2024

- Enhanced Iron Sight Visuals (w_ak74.ltx):
  - Reverted adjustments to zoom_offset, grenade_normal_zoom_offset, and grenade_zoom_offset to improve visual consistency when aiming with iron sights and the reduced zoom effect.
  - Increased scope_zoom_factor to 75 to match other iron sight weapons, ensuring a consistent visual experience.
- Balanced Player Protection (actor.ltx):
  - Aligned fire_wound_immunity values across difficulty levels with Clear Sky's values for a more balanced gameplay experience.
  - Increased player bullet protection:
    - [actor_immunities_gd_novice]: 0.5 -> 0.1
    - [actor_immunities_gd_stalker]: 0.65 -> 0.2
    - [actor_immunities_gd_veteran]: 0.8 -> 0.4
    - [actor_immunities_gd_master]: 1.0 -> 0.6

v0.1 - 04/06/2024

- Gameplay Adjustments:
  - Ballistics: Decreased hit_probability_max_dist from 10 to 3 and increased air_resistance_k from 0.4 to 1, aligning them with Clear Sky and Call of Pripyat (CS/COP) values.
  - NPC AI: Adjusted behavior to resemble CS AI for a more consistent experience.
  - Alternative Ballistics: Implemented core features replicating functionality from SRP v1.1.4. For detailed descriptions, refer to the "SRP v1.1.4 - Optional Features.txt" (link here: <https://github.com/Decane/SRP/blob/a4e5f513c87054973684da932b2664079157bdf1/SRP%20v1.1.4%20-%20Optional%20Features.txt>).
  - Cut Weapons: Adjusted properties for cut weapons (TOZ-34, Browning Hi-Power, and Beretta) to potentially enable full in-game restoration.
- Weapon Adjustments:
  - Unique Weapons: Modified properties for unique weapons with adjustments ranging from 15% to 30% depending on the existing property.
  - Weapon iron sights: Improved visuals by adjusting z-offset for a better appearance when using iron sights with the new reduced zoom effect.
- Other Changes:
  - Enhanced NPC Vision: The NPC eye range has been increased from 80 to 100, aligning with Call of Pripyat. This allows NPCs to detect the player and other characters from a slightly longer distance.
  - AI Accuracy: Implemented 100% hit probability for AI, ensuring damage on any successful shot.
  - Improved Zombie Stealth: Tweaked zombie AI to enhance stealth gameplay. Players can now effectively hide behind vegetation from non-alerted zombies.
  - First Super Bullet Mechanic (Disabled): Removed the "super bullet" mechanic (matches COP) where the first aimed shot dealt significantly higher damage, particularly to the head. This ensures consistent weapon behavior based on base damage values.



📌 Test Case 6: Weapon Purchase System

Test Case ID: VAL006
Feature: Buy Phase / Economy
Description: Ensure players can buy weapons during the buy phase and receive the purchased items correctly.
Preconditions: The player has enough in-game currency.
Test Steps:
	1.	Enter a match and wait for the buy phase.
	2.	Open the buy menu (B key).
	3.	Purchase a primary weapon, a secondary weapon, and a shield.
	4.	Exit the buy menu and check if the items appear in the inventory.
Expected Result: The purchased weapons and shields should be available for use in the round.

📌 Test Case 7: Weapon Firing & Reloading

Test Case ID: VAL007
Feature: Combat Mechanics
Description: Verify that weapons fire correctly and reload animations work.
Test Steps:
	1.	Equip a rifle (e.g., Vandal).
	2.	Aim and shoot at a target.
	3.	Check if bullets register and deal damage.
	4.	Reload the weapon and observe the reload animation.
Expected Result: Weapons should fire properly, and the reload animation should play without glitches.

📌 Test Case 8: Agent Abilities Functionality

Test Case ID: VAL008
Feature: Agent Skills
Description: Ensure that agent abilities function as expected.
Test Steps:
	1.	Select Jett in a match.
	2.	Use Dash (E) to move forward.
	3.	Use Updraft (Q) to jump high.
	4.	Check if ability animations and cooldowns work properly.
Expected Result: All abilities should execute correctly and follow cooldown rules.

📌 Test Case 9: Spike Planting & Defusing

Test Case ID: VAL009
Feature: Objective Mechanics
Description: Verify the spike can be planted and defused correctly.
Preconditions: Player is on the attacking side and has the spike.
Test Steps:
	1.	Reach a bomb site (A or B).
	2.	Hold 4 to plant the spike.
	3.	Switch to the defending side and attempt to defuse it.
Expected Result: The spike should be plantable at designated sites and defusable within the correct time frame.

📌 Test Case 10: Ping & Network Stability Check

Test Case ID: VAL010
Feature: Network Performance
Description: Ensure that latency does not cause major gameplay issues.
Test Steps:
	1.	Play a match and monitor the ping (TAB key).
	2.	Observe whether shots register correctly and player movement is smooth.
	3.	Check if there are rubberbanding or disconnects.
Expected Result: The game should run smoothly with stable network performance.

📌 Test Case 11: Audio Functionality & Voice Chat

Test Case ID: VAL011
Feature: Audio & Communication
Description: Verify that in-game audio and voice chat work properly.
Test Steps:
	1.	Check gun sounds, footsteps, and ability sounds.
	2.	Enable push-to-talk voice chat and speak to teammates.
	3.	Check if teammates can hear and respond.
Expected Result: Audio cues should be accurate, and voice chat should work without distortion.

📌 Test Case 12: Performance (FPS & Graphics Settings)

Test Case ID: VAL012
Feature: Game Performance
Description: Verify FPS stability under different graphics settings.
Test Steps:
	1.	Open settings and set Graphics Quality to High.
	2.	Play for 10 minutes and monitor FPS (F3 key).
	3.	Lower settings to Low and check for improvements.
Expected Result: The game should run at a stable FPS according to hardware capabilities.

📌 Test Case 13: Matchmaking & Queue System

Test Case ID: VAL013
Feature: Multiplayer Matchmaking
Description: Ensure players can queue and find matches correctly.
Test Steps:
	1.	Click Play and select Unrated Mode.
	2.	Click Find Match and check queue time.
	3.	Accept the match and verify the loading screen appears.
Expected Result: Players should be matched within expected queue times.

📌 Test Case 14: AFK Detection & Penalties

Test Case ID: VAL014
Feature: Anti-AFK System
Description: Verify that the game detects AFK players and penalizes them.
Test Steps:
	1.	Start a match and stay idle for 5 minutes.
	2.	Observe if a warning message appears.
	3.	Check if the system applies a penalty (e.g., XP reduction or queue restrictions).
Expected Result: The AFK system should detect inactivity and apply penalties.

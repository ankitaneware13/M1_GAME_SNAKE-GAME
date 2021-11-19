**Snake Classic system requirements**

- Memory: 4 GB.
- Graphics Card: ATI FireGL T2-128.
- CPU: Intel Pentium 4 2.00GHz.
- File Size: 20 MB.
- OS: Windows 7/8/10.

**Basic example, not complete, and assuming desktop:**

**Functional Requirements:**

1. WASD keys for W-Up, A-Left, S-Down, D-Right change the snake's direction.
1. The sake has a velocity in the direction it is moving. That velocity increases with time. (Provide function of time for detailed requirement.)
1. Randomly place power-ups:
   1. Slow snake velocity.
   1. Food makes the snake longer.
   1. Bonus targets gain bonus points.
   1. etc.
1. If the sake collides with the snake the round ends and a new round starts.
1. At the end of rounds, the score is registered as the player’s highest if it is better than any recorded before. The highest registered score is tracked between all players on a leaderboard.
1. Log in to identify the player. (Details should include username/password requirements, is two-factor auth needed, should obscene words be allowed as usernames? etc..?)
1. Options menu to set music and sound effects volumes. Color scheme?

**Non-Functional Requirements:**

1. On cutting-edge computers, as of 2010, it should get a 40 FPS refresh rate.
1. The leaderboard needs to support 9 million concurrent users.
1. The leaderboard must be updated within 2 min after a new high score is registered by a play.

This is the idea. For real game development documentation, you would also want some discussion about monetization and promotion. You would want some details about the look and feel. (Is it neon colors, does it use a disco beat to the music/effects, should be it slower and more casual or fast and intense? Etc…)

A good game design document is more than requirements. But, the requirements are a major part of it. Functional requirements are about what it should do. Non-Functional requirements are about how well it should perform on which platforms.


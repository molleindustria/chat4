# Visual Chat part 3b

This iteration adds a quick login option for testing purposes (QUICK_LOGIN variable) and dynamic room creation.

In multiplayer games that require a certain number of players there is typically a lobby section in which users can host their games or join existing ones.

We'll implement a rudimentary an UI-less version of it that automatically creates rooms and assigns users to them after a given limit is reached.

Right now if a user disconnects their slot frees up for the next user. Depending on the experience you'll have to implement a logic for when users leave mid-game. Are they taken over by an AI? Does the game restart and waits for the right amount of players? Etc

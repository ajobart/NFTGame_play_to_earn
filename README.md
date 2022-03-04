# NFTGame_play_to_earn

A smart contract to create small play to earn game.
You can copy/paste to try it on Remix.

### Features

- Create a character

- View your characters

- Sell your character as an NFT

- Healing : allows to recover 50 points of life. You can only heal yourself every 60 seconds maximum. You can't heal a character whose life is 0 because he is dead

- Fight : allows you to fight another user's character

- You can fight a character if one of them has not fought in the last 60 seconds

- You can only fight a character that you own

- You can't have 2 of your own characters fight together

- You cannot fight a dead character

### The principle

- You can create up to 5 characters per Ethereum account

- You can fight with one of your characters, the character of another user

-Character attributes :

- Attack
- Defense
- Life
- Experience
- Date of the last healing (healing regenerates hp)
- Date of the last fight

### The three types of factions

**The orcs**

- Attack 20
- Defense 15
- Life 100
- Experience 1 (at the beginning)

**Humans**

- Attack 13
- Defense 25
- Life 80
- Experience 1

**Elves**

- Attack 17
- Defense 20
- Lifetime 70
- Experience 1

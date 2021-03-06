![Cryptower](https://github.com/fima2016/Cryptower/blob/master/1500x500.jpeg)

# Cryptower

А game that allows you to simulate price fluctuations, traders’ behavior and formation of price patterns. An infinite number of players can participate in the Cryptower game and anyone can enter or exit the game at any time.

### Description

The goal of the game is to make a profit by building a tower. Each player must add at least one building block level to the height of the tower — this simulates a buy. To add a level to the tower, a player must deposit a number of tokens that is equal to the current height of the tower in levels plus one (1). A player can also remove levels from the top of the tower — this simulates a sell. When a player removes a level, he/she receives tokens equaling the height of the tower (in levels) at the current moment. At most, a player can remove only the number of levels that he/she built and not yet removed (2). To end the game a player removes all the levels that he/she previously built.</br>

The value of the top level is exactly the same as the number of floors in the tower and the total value of the tower is determined by a defined formula (3).</br>

The game makes economic sense, because players who earn tokens will be able to sell them for profit on an exchange (in the future).</br>

All the formulas are described in Appendix III and more detailed rules of the game are in Appendix II. The study of price fluctuations is very interesting and the price fluctuations of the tower will resemble price fluctuations in the stock market. For analysis and prediction of fluctuations, technical analysis can be used, the same as that used to analyze and predict fluctuations for stock prices, indices and other assets. In financial markets, the behavior of prices is subject to various fundamental laws, and in the game Cryptower everything is simplified to the behavior of a crowd.

### Appendix I: Detailed rules of the game

The object of the game is to make a profit by building a tower;</br>
The number of players is unlimited;</br>
The height of the tower is equal to the number of levels in it;</br>
A player can build one or more levels;</br>
A player can only remove the number of levels he/she has previously built;</br>
A player can either build or remove levels in one turn, but not both;</br>
Players do not have to wait their turn; whoever makes the move first goes first.</br>
There is a maximum number of level a player can build at any one time. At the very beginning of the game, you can build only one level, but starting with n > 1 (where n is the number of levels in the tower), you can build no more than the integer part of the binary logarithm n;</br>
In order for a player to build a level, the player must put tokens in the amount equal to the height of the tower plus one token;</br>
When a player removes a level, he/she receives tokens equaling the height of the tower (number of floors) at the current moment.</br>
When a player removes a level, the tokens are credited to the player’s personal account.</br>
If a player leaves the game, all his levels are sold and he receives tokens in an amount equal to the price of the levels as determined by the tower ‘s height.

### Annex II: Formulas

```Ma = s + s * (s + 1) / 2``` (1),

where **Ma** is the number of tokens that the player must deposit, **s** is the number of levels that a player wants to build, **h** is the height of the tower, new tower height: h = h<sub>1</sub> + s

```Mp = s * h - s * (s - 1) / 2``` (2),

where **Mp** is the amount of money that a player receives from the bank, new tower height: h = h<sub>1</sub> - s

```C = h * (h + 1) / 2``` (3),

where **C** is the amount of money in the bank, depending on the height of the tower.

### Annex III: Interface

Each player has a private account, where the following functionality is available:</br>
Wallet with tokens;</br>
Replenishment of the wallet;</br>
The amount of money in a common bank for each tower;</br>
The maximum number of levels the player is allowed to build currently;</br>
Number of levels built by the player in the tower (those that can be removed);</br>
Interface for building / removing levels;</br>
History of price changes of the tower.

### Beta

**Beta has been released:** https://cryptowergame.com

If you are interested in the game, you can join the group:</br>
Telegram: https://t.me/cryptowergame</br>
Bitcointalk: https://bitcointalk.org/index.php?topic=3418629.0</br>
Twitter: https://twitter.com/CryptowerGame</br>
Reddit: https://www.reddit.com/r/cryptower/</br>

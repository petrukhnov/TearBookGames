version 0.1

# Similar words

Simple game for 3-5 players that uses pages from books to provide gameplay content.

To win the game, player should get the maximum number of points at the end.

## Setup

1. Empty lined paper sheet.
2. Your most valuable book, that will be destroyed.

Split sheet of paper to several columns: 1st should be longer for writing words, others for each player to write score.
Tear one sheet from the book. Best if there are multiple rows of the text.

## Gameplay
Game play in rounds that consist of turns. To select the first player, look at the first letter on a page. The name that comes next in the alphabet after this letter becomes the first player.
Write the first word on a page to the sheet. Strike out all lines that have less than 3 words.

During turn, player:
1. Select any first word from any of the lines, so there are as many matching letters as possible. 
2. He writes that word on the next line, and then counts how many letters new word have matching previous word.
3. Calculate points.
4. Strike out used word from the text.

E.g. if the first word is "shopkeeper", selecting word "tests" will give 3 points total, one for each of the letters: e,s,s. Write points in the corresponding player column.
Then the next player clock-wise continues.
When each player completed turn, the round ends, draw line below the last word. Player who has the fewest points during previous round picks who will start the next round (if tie, last one of them).   
Play 5 rounds.

Rules for writing words.
1. Word should be first in the line.
2. Word should be longer than 1 character.

Some rules could be ignored if combo is used (if mentioned in combo description).

Combos (declare before show word that you will write).
1. Last word in the row -> play another turn.
2. Single letter before selected word -> allow picking any previously written word to compare letters.
3. Number after selected word -> use one of its digits as bonus points.  

## Mistakes

During the play, there could be mistakes. E.g. player writes or strikes wrong word.
If the mistake is noticed, player points for this turn are canceled and all his remaining turns ended immediately.


## Time

Sometimes game could be slow, as people can't keep all available words in memory. To speedup game, consider the following approaches.
- Limit the number of turns to 5.
- Set time limits like in chess (e.g. 5 total minutes for each player). If player is out of time, others could continue while they still have time left.
- Pick pages with smaller number of rows.
- If you have timer - set limit to 30 seconds per player turn. If the player announces word withing limit - he gets +1 point, if not, he has to write the first available word on the page.


## Example of the gameplay

[example1.md](example1.md)

version 0.1

# Cross words combat


Strategy game that uses pages from books to provide gameplay content.

To win the game, player needs to enclose cell areas with own color. Each captured cell is worth 1 point. Who have most points at the end of the game - wins.

## Setup
1. Empty cell/grid paper. It would be referred to as gameboard below.
2. Your most valuable book, that will be destroyed.
3. Two pens of different colors (black/blue combination is not very good).

Sit side by side (make it easier for the first play).
Each player tears one sheet from the book. Best if there are multiple rows of text. Each player picks the side of the sheet.
Calculate starting positions on grid paper. E.g. if the whole paper divided in 3*3 grid, first player start position would be on top of central cell, and 2nd player - on the bottom of central cell.
Each player picks the very first work on his sheet, and writes town horizontally in his starting position.

## Gameplay
Game play in turns. First is one, who writes word on the bottom part.
During turn player picks any word that is in first on any row, and he could write it to the sheet so it crosses or continues his color letters.
He shows that word to the opponent, then he writes it to the game board, and strikes it from the sheet.

Rules for writing words.
1. It should cross at least one letter of own words.
2. It can't enter any captured area.
3. It should be the first unstriked(unused) word of the row.
4. It should not touch vertically or horizontally any of the opponent areas or letters (diagonally ok).
5. It should add at least one new letter to the game board.

Some rules could be ignored if combo is used (if mentioned in combo description).

Combos (declare before show word that you will write).
1. Write word, so it crosses other color. Ignore rule 4. Paint over opponent cell with your color. It is a captured cell. Do another turn.
2. Write word, so crosses 2 letters of other color. Ignore adjustment rule (rule 4). Paint over opponent cells with your color. Do another turn, during it, pick any words from your sheet (ignore rule 3).
3. If words enclose the area, then are marked as captured. Mark its inner perimeter (only empty cells) with own color. Play another turn, but you could only use words that have fewer letters than captured area.
4. If there is one or more numbers immediately after the word, you could play another turn. During that turn you could use only word that has the exact number of letters as one of the digits.
5. If there is a single separate letter right after the word, do another turn. During that new turn, you could use only words started with that letter.

Other notes: ignore punctuation and other symbols that are not letters or numbers. E.g. treat them the same as space - separators.

## Mistakes
During the play, there could be mistakes. E.g. player writes a letter in the wrong cell, or miscalculated length of the word.
If the mistake is noticed, do the following:
1. All turns of the current player are ended immediately.
2. All invalid letters that were written during that turn as marked as captured by opponent (paint over with color).
3. Opponent gets additional turns equal to the number of invalid letters. 

## Time

Sometimes game could be slow, as people can't keep all available words in memory. To speedup game, consider the following approaches.
- Limit the number of turns to 30.
- Set time limits like in chess (e.g. 10/10 minutes). If player out of time, other could continue while he still has time left.
- Pick pages with smaller number of rows.


## Example of the gameplay

[example1.md](example1.md)
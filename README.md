# Pocket Snake

The classic Snake game in a single HTML file, styled like an old monochrome LCD phone. No build step and no libraries: just HTML, CSS and JavaScript.

## Play

Download `snake.html` and open it in any modern browser. It works offline. The only thing it loads from the internet is its pixel font, and it falls back to a system font without one.

## Controls

| Action | Keyboard | Phone / mouse |
| --- | --- | --- |
| Steer | Arrow keys or `W` `A` `S` `D` | Swipe on the screen, or the keypad arrows |
| Pause / resume | `Space` or `P` | **Pause** or **OK** |
| Select in menus | `Enter` | **OK**, or tap an option |
| Open the menu | `Esc` or `M` | **Menu** |

In the menu, use up and down to choose a row and left and right to change it.

## Game modes

- **Classic:** play until you crash.
- **Time attack:** score as much as you can in 60 seconds.
- **Maze:** eat 10 dots to clear each maze. There are 5 layouts, and each level is faster.

## Options

- **Board size:** small (14 × 14), medium (20 × 20) or large (26 × 26).
- **Speed:** 1 to 5. Each dot is worth your speed level in points.
- **Edges:** walls end the game, or wrap lets you come out the other side.
- **Easy mode:** a slower start, and biting your tail cuts it off instead of ending the game.
- **Theme:** Classic, Night or Contrast.

## Scoring and extras

- **Bonus ring:** appears after every 5th dot. The faster you reach it, the more it's worth.
- **Power-ups:** `S` slows the game for 8 seconds, `2` doubles your points for 10 seconds, and `-` shrinks the snake by 4.
- **One continue:** once per game, after a crash, you can rewind 3 steps and keep going.
- **3-2-1 countdown:** before every start and after every pause.

## Scores, stats and badges

The **Scores & badges** screen has four tabs:

- **Top 10:** your best scores in each mode, with your name.
- **Everyone:** a shared leaderboard (see below).
- **Stats:** games played, dots eaten, best length, average score, time played and more.
- **Badges:** 13 achievements, such as reaching length 40 or clearing maze level 5.

Top-10 lists, stats and badges are saved in your browser, so they stay on that device.

### Shared leaderboard

The **Everyone** tab only works when the game runs as a published page on Claude, where it keeps each player's best score per mode. When you open `snake.html` directly, that tab says so, and everything else works normally. Easy mode scores are never posted to the shared board.

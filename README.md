# Daily At-Bat ⚾

A daily baseball hitting game. Each day you play one inning in a new themed ballpark. You keep batting until you make 3 outs, and the goal is to score as many runs as you can.

**Play:** https://jamesgregory5-svg.github.io/daily-at-bat/

- **One inning, 3 outs.** Strikeouts and batted balls that get fielded count as outs. Four balls is a walk. A foul with two strikes doesn't strike you out.
- **An endless line of pitchers.** You face a new pitcher every plate appearance. Each one has a name, a throwing hand, and a pitch mix (4-seam fastball, sinker, cutter, slider, curveball, changeup, splitter). The longer the inning goes, the faster and nastier they get, with more breaking balls and a smaller zone. Every player gets the same pitchers on the same day.
- **Simple base running.**
  - A single moves every runner up one base, and a double moves them up two.
  - A triple clears the bases, and a home run scores everyone.
  - On a walk, only the forced runners move up.
  - Deep fly balls can score a runner from third as a sac fly, and some ground balls turn into double plays.
- **Mini diamond HUD** with animated runners, 3 out dots, a big run count, and your current hit streak. Every run gets a score pop, and grand slams get fireworks.
- **Records** are saved on your device and shown on the title and game-over screens: most runs (daily best and all-time best), longest HR, most HRs in a game, longest hit streak, career runs, career HRs, and your day streak. A **NEW RECORD!** banner appears as soon as you break one.
- **Daily mode** gives you one ranked inning per day. Your progress saves after every pitch. If you reload during a pitch, that pitch counts as taken.
- **Share text**, for example `Daily At-Bat #1 ⚾ 7 runs · 2 HR · 3 outs`, plus one emoji per plate appearance.
- **Endless / Free Play** gives you random pitchers. It counts toward all-time records but not toward your daily inning. **Practice** lets you pick the pitch type, speed, location, and pitcher hand, and counts toward nothing.
- **Controls:** tap **SWING**, tap the field, or press **space** when the marker hits the sweet spot. Early swings get pulled, and late swings go the other way. The color of the pitch trail shows the pitch type. You can turn on manual aim with a contact circle in settings (mouse, arrow keys/WASD, or drag).

Everything is in one `index.html` with no outside requests. You can download it and open it as a local file.

The format is inspired by the classic "bat until three outs" browser baseball games. All art, sound, and code here are original.

# Getting started

[Download the game](https://github.com/RyanFDev/putt-together-releases/releases/latest)
 · [Controls](CONTROLS.md) · [Multiplayer](MULTIPLAYER.md)

## Install

Download the Windows game ZIP from the latest release's **Assets** section.
Its name starts with `PuttTogether-` and ends in `windows-x86_64.zip`.
GitHub's **Source code** downloads are not the game.

Extract the whole archive into a writable folder, such as a folder under your
user account. Run **PuttTogether.exe** from the extracted folder. Keep all the
files together; the executable needs the data and library files beside it.

The beta is for 64-bit Windows with a keyboard and mouse. It doesn't need a
Godot installation or a player account. The executable is currently unsigned,
so Windows may show a warning. Use the download from this repository; don't
disable Windows security or your antivirus to run it.

## Play your first hole

1. Choose **Explore parks**, then open **Pocket Links**. It has three holes and
   is a small place to learn the controls.
2. Choose **Play a round** and start a solo round. You can add bots if you'd like
   company. For a group, each person chooses **Ready to play** before the host
   starts.
3. Press **1** for Putter and **F** to find your ball. Face roughly along the line
   you want to play.
4. Hold **left mouse** to address the ball. Keep it held, move the mouse **right**
   to draw the putter back, then **left** to swing through. A small, slow stroke
   is a useful starting point. Releasing the button leaves the stance.
5. After holing out, choose **Next hole**, or **Finish your round** on the final
   hole. When everyone has finished, open the scorecard for results and choose
   **Back to building**.

You can also practise between rounds: use **P** to place a practice ball on a
clear playing surface, or aim at a tee and press **E**. Click to confirm practice
placement; right mouse cancels it.

## Line up a shot

While addressing the ball, keep left mouse held and hold **right mouse** to look
down the line. Move left or right to adjust aim and up or down to tilt the view.
Release right mouse to return to the ball, then make your stroke. **Q/E** gives
smaller aim adjustments.

While holding right mouse in this aiming view, use the **wheel** to change the
distance reference; **Shift+wheel** makes finer changes. The line is a guide,
not a promise: your stroke, the slope, obstacles and other balls affect the shot.

**Settings** offers Easy and Advanced putting, left- or right-handed stance,
stroke direction and sensitivity. Easy guides the putter's contact. Advanced
lets you hit off-centre or miss. Handedness and mouse stroke direction are
separate settings. Reduce motion and Reduce flashing lights are there too.

## Build something of your own

Choose **Create a park** for an empty outdoor garden or indoor arcade. You can
also change an included course and use **Save as** to keep your own version.

- **B** opens the piece library. Choose a piece, aim at its position and click
  to place it. Right mouse cancels a preview.
- **Q/E** selects the visible adjustment, such as Rotation or Height. The
  **wheel** changes it; hold **Shift** for finer steps. **Tab** opens tool options.
- **2** selects existing pieces. **M** moves a selection, **Ctrl+D** copies it,
  and **Ctrl+Z** undoes your edit.
- **4** equips Terrain. Choose a brush in **Tab**, then hold left mouse to shape
  or paint the ground. Move existing pieces and balls clear before sculpting
  underneath them.
- **H** opens the hole list. **Add hole** places a tee and then its cup. Give the
  hole a name and par; each hole needs both markers before you can start a round.
- **Ctrl+S** saves the park. Use **Save as** for a separate copy.

The [controls guide](CONTROLS.md) covers drawing paths, resizing pieces,
blueprints, favourites and the other tools. **F1** opens the current bindings
inside the game.

## Keep your work

Parks are saved in `%APPDATA%\PuttTogether\parks`. Settings, blueprints and
recovery copies are under the same `PuttTogether` folder. Paste that path into
File Explorer's address bar to find them.

The game keeps periodic recovery copies of changed parks. If you lose unsaved
work, try **Explore parks → Recovery copies → Recover park**, then save the
recovered park to your library. A recovery copy doesn't replace using Save,
and it doesn't resume a running match.

For updates, return to the main menu and choose **Check for Updates**. Choose
**Update and Restart** when you're ready, or **Later** to keep playing. Updating
restarts the game and ends any shared session, so finish the session together
before the host updates. Saved parks and personal settings stay in place.

[Connection help](MULTIPLAYER.md) · [Troubleshooting](TROUBLESHOOTING.md)

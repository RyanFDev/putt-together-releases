# Controls and putting

These are the default controls. Press **F1** in the game for the searchable reference, your current bindings and keyboard remapping. Your control and putting preferences are saved on your computer.

## Walk and find your ball

| Control | Action |
| --- | --- |
| W / A / S / D | Walk |
| Mouse | Look around |
| Shift | Sprint |
| Space | Jump |
| F | Find your ball |
| E near a tee | Place your practice ball at the nearest clear numbered tee slot |
| E at a drawbridge button | Lower the bridge or extend its open timer |
| E facing a Message Sign | Edit its text while nearby |
| P | Place a practice ball between rounds |
| Backspace | Retry your lie; a penalty applies during a scored round |
| N | Next hole / finish round after holing out |
| Escape | Cancel the current action or release the mouse |
| Alt+Enter | Toggle fullscreen and restore your previous window |

## Make a putt

1. Choose **1 — Putter**, face the direction you want to shoot, and wait for your ball to settle. **F** helps you find it.
2. Hold **left mouse** to address your ball. Keep holding it throughout the stroke.
3. Move the mouse **right to draw back**, then **left to swing through**. A quicker swipe produces a harder shot. Release left mouse to leave the stance.

To inspect the line, hold **right mouse while still holding left mouse**. Move left/right to aim and up/down to tilt the view. Release right mouse to return to the ball with that aim retained. **Q/E** also nudges your aim while addressing.

Whenever **Putter is equipped**, the **wheel** adjusts shot power by **0.5 m**;
**Shift+wheel** uses **0.05 m**. The remappable **[ / ]** keys decrease/increase
it with held-key repeat. No mouse buttons need to be held. The metres are a
flat-ground reference; stroke pace, contact and the course still determine the
actual distance. Adjusting power briefly shows a **Shot power** card and roll
preview. Power locks when the club first moves; release left mouse to leave the
stance and adjust again.

The preview estimates the current course, including slopes, obstacles and other
balls. A partial path is not a promised stopping point. **G** toggles additional
guides. After a long input stall, an unfinished stroke is cancelled; release the
button and start a fresh stance.

In **Settings → Putting**, choose **Easy** for guided contact along the stroke axis, or **Advanced** for sideways movement, glancing hits and possible misses. A miss does not count as a stroke. Handedness changes your stance. The through-stroke direction is a separate setting: the default is left, and you can choose another direction or a custom angle. Draw back in the opposite direction. Swing sensitivity is adjustable too.

You can strike only your own ball, but rolling balls can collide with one another.

After holing out in a round, press **N** to advance or finish. With Putter
equipped, **Tab** releases the cursor and focuses **Next hole / Finish round**;
click or press **Enter**. These shortcuts use your current remapped bindings.

## Build tools

| Control | Action |
| --- | --- |
| 1 / 2 / 3 / 4 / 5 / 6 | Putter / Select / Pieces / Terrain / Draw / Water |
| B | Open the piece library |
| Tab | Open tool options; with Putter equipped after holing out, focus Next hole / Finish round |
| Q / E | Select the previous / next visible adjustment |
| Wheel | Change the highlighted adjustment |
| Shift+wheel | Change that same adjustment more finely |
| Alt+1–6 | Equip a favorite piece |
| G | Toggle guides |
| C | Toggle piece/path connections |
| V | Toggle world-grid snapping |
| Shift+V | Show or hide the placement grid independently of snapping |
| H | Open the hole list |

Use the library to choose a piece, then **left-click** to place its preview.
**Right-click** cancels. **Q/E** selects Rotation, Elevation or an individual
supported size axis, such as Width or Length. The wheel changes the highlighted
setting; **Shift** refines it. **Elevation** moves the whole piece vertically.
**Tab → Options** contains separate numeric fields for supported dimensions;
**Reset dimensions** restores their original sizes. To resize an existing piece,
select it, press **M**, adjust its dimensions and click to confirm.

While placing, hold **Shift** to temporarily suspend connections and grid snapping.
Releasing it restores your switches. The visible grid stays available for manual
alignment, with quarter-metre spacing and stronger metre lines. Drawn path ends
can dock against a curb as a fitted access ramp.

The drawbridge supports **Deck width**, **Gate height** and **Span length**.
Its settings also control the open duration (2–30 seconds). Either button lowers
the bridge; pressing again extends the timer or reverses a closing bridge.

With **Select**, click a piece or **Shift-click** to add/remove pieces from a group. **M** picks up the selection; click to confirm its new position. Use **Ctrl+D** for a copy preview, **X** to mirror a supported single piece, and **Ctrl+R** for a repeated row or curve. **Delete** starts batch removal: click to mark or unmark pieces, then **Enter** confirms. **Ctrl+Z** undoes your edit; an undo can be refused if it would overwrite a friend's newer change.

In **Terrain**, hold left mouse to brush and use middle mouse to sample ground height; right mouse cancels a pending ramp. **Draw** uses clicks for endpoints and right mouse to cancel. **Water** uses held left/right mouse to spray/drain. Middle mouse samples a piece where the active construction tool supports it.

## Hole boundaries, routes and portal pairs

Open **Course [H]**, choose a hole and select **Edit boundaries**. **Add OOB zone**
places a forbidden box; **Add playable box** is inside the boundary editor.
Boundary rules check where a ball rests. An invalid round lie returns to a legal
prior lie with a one-stroke penalty; practice recovery is free. Use **P** away
from a tee for free practice without a hole assignment. Placing on a tee mat or
using **E** at a tee binds practice to that hole again.

For bot guides, choose **Add checkpoint** or **Edit bot route** in **Course [H]**.
Click supported ground to extend the trail. Click a pylon to select it, **M** to
move or resize it, and **Delete** to remove it. **Shift-click** a pylon starts a
branch; **Shift-click** a route line inserts a pylon. In Select, press **E** on
two guides to join them. Switch to the normal Select tool to leave route editing.

While placing or moving a checkpoint, **Q/E** and the wheel adjust Region width,
Region height or Region depth; **Tab → Options** also has numeric fields.
**Checkpoint behavior** defaults to **Pass through region**. Choose **Stop in
region** to require a resting ball inside the box for that guide visit. It does
not stop the ball for you. Guides apply to experimental bots; human scoring still
uses the cup.

To pair portals, equip **Select**, press **E** on an entrance and then its exit
(or the reverse). Pair numbers identify partners independently of hole numbers.
Unpaired endpoints are inactive; Escape or right mouse cancels linking.

## Bots and overlays

In **Play a round**, the host can enable **Use experimental bot AI** before
starting. It is **off by default** and applies for that round. Bot guides apply
only with this option enabled.

**F2**, or **Settings → Display → Debug overlays**, opens local switches for hole
boundaries, flipper trigger zones, magnet fields and bot planning targets. All
start off. **Hide all** clears them; F2, Escape or Close dismisses the panel.
These switches affect your display; boundary and prop rules still apply.

## Equipment and display

Open **Customize** from the menu or **Settings → Display → Customize ball & putter**. Choose the ball color and pattern,
then the putter style and finish. Use the 3D preview, then **Apply** to save or
**Cancel** to keep your old selection. Friends see the equipped choices. All
starter choices are unlocked and have identical putting physics.

The game fills the window at different aspect ratios. In **Settings → Display**,
choose borderless or exclusive fullscreen, or select a window size and choose
**Apply resolution**. **Alt+Enter** toggles the selected mode;
returning to windowed mode restores its prior size and position. The operating
system and graphics backend determine exclusive presentation behavior.

## Blueprints, saves and recovery

Select a group, press **Ctrl+B** or open **B → Blueprints**, give it a name and choose **Save selection**. Use **Place** to reuse it in another park. Blueprints contain pieces, not sculpted terrain. Include both tee and cup when copying a whole hole.

Press **Ctrl+S** to save your park. **Save as…** in the menu creates a separate copy. Saving an included park creates an editable personal copy.

Changed parks also receive automatic recovery checkpoints. Check the save status before leaving: continuous terrain work can delay a checkpoint. To restore one, open **Explore parks → Recovery → Recover park**, then save the recovered park to keep it. Recovery preserves the course, not a running round.

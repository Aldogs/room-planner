# Aldo's Room Planner

A 3D planner for my bedroom. You can walk through the room, move furniture on a floor plan, and compare layouts and bed options before moving anything for real.

**Open it:** https://aldogs.github.io/room-planner/

It runs in the browser, so there's nothing to install. It works on a computer or a phone, in English or Spanish.

## What it does

- **Floor plan:** drag furniture to move it. Double-click an object to rename it, and Cmd + click (Ctrl + click on Windows) to select several and move or turn them together.
- **3D view:** orbit around the room from outside, or walk through it from the door, the window or the bed. Switch between day and evening, and open or close the door and roller blind.
- **Layouts:** compare today's room with four alternatives:
  - **A** turns the desk into the window corner.
  - **B** moves the bed into a corner.
  - **C** puts the headboard on the shelf wall.
  - **D** puts the headboard on the TV wall.
- **Bed test:** try a matrimonial, queen or king frame with the current headboard, a king headboard or none. A grid compares every layout with every bed setup.
- **Checks:** the planner flags furniture that collides, blocks the door, closet or window, or leaves a walkway under 60 cm. It also tracks how much of the window stays clear.
- **Extras:** a monstera that sits on top of any furniture, and a mirror that hangs on any wall at any height. Both start outside the room.
- **Shared layouts:** add your name, save an arrangement, and everyone with the link sees it straight away, on any browser or device.

## Controls

| Action | How |
|---|---|
| Move an object | Drag it on the plan, or in the 3D outside view |
| Turn an object | **Turn 45°** / **Turn 90°** buttons, `R` (90°), `Shift` + `R` (45°), or the round handle |
| Select several | `Cmd` + click (`Ctrl` + click on Windows) |
| Rename | Double-click the object |
| Nudge | Arrow keys (`Shift` for 1 cm steps) |
| Walk | `W` `A` `S` `D`, hold `Shift` to go faster |
| Look around while walking | Arrow keys, or drag |
| Undo / redo | `Cmd` + `Z` / `Cmd` + `Shift` + `Z` (`Ctrl` on Windows) |

## The room

- 3.80 × 3.70 m.
- The ceiling slopes from 3.00 m at the TV wall to 2.40 m at the window wall.
- The window is 1.70 m wide and 1.23 m tall, starting 87 cm above the floor.
- The door is 80 cm wide, and the closet is 1.27 m wide and 68 cm deep.
- Furniture sizes are measured, apart from a few estimates such as the TV stand height and the headboard thickness.

## Good to know

- **Saving:** saved layouts are stored in a shared Firebase database. Anyone with the link can see, load and delete them. Unsaved edits stay in your own browser.
- **Analytics:** the page uses Google Analytics through Firebase to count visits.
- **Internet:** the page needs an internet connection, because the 3D library and fonts load from the web.
- **Built with:** a single `index.html` file using [three.js](https://threejs.org/) for the 3D view and [Firebase](https://firebase.google.com/) for shared layouts.

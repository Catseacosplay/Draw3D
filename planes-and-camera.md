---
layout: page
title: Planes and the World Camera
description: How to move the camera in Draw!3D and how planes work, including straight planes, curved planes, 3D shape planes and the Planes list.
permalink: /planes-and-camera/
---

Draw!3D is a 3D drawing app for Android tablets. This guide covers the one idea that makes it click: **every stroke lands on a flat or curved sheet floating in 3D space, called a plane, and you move the camera to choose where that sheet goes.**

On this page:

- [How do I move the camera in Draw!3D?](#how-do-i-move-the-camera-in-draw3d)
- [What is a plane in Draw!3D?](#what-is-a-plane-in-draw3d)
- [How do I make a wall to draw on?](#how-do-i-make-a-wall-to-draw-on)
- [How do I draw on a curved surface?](#how-do-i-draw-on-a-curved-surface)
- [How do I draw on a sphere, cube or other 3D shape?](#how-do-i-draw-on-a-sphere-cube-or-other-3d-shape)
- [How do I go back to a plane I drew on before?](#how-do-i-go-back-to-a-plane-i-drew-on-before)
- [Example: build a tiny garden](#example-build-a-tiny-garden)
- [Common questions](#common-questions)

## How do I move the camera in Draw!3D?

**One finger draws. Two fingers move the camera.**

- **Zoom:** pinch two fingers in or out.
- **Pan:** slide two fingers together across the screen.
- **Turn around your drawing:** tap the Orbit switch at the bottom of the screen so it reads **Orbit: Unlocked**, then drag with two fingers. Tap it again to go back to **Orbit: Locked**, so panning never turns the view by accident. Orbit starts locked on every new canvas.

While two fingers are on the screen nothing is drawn. If your first finger had just started a stroke when the second finger touched down, that stroke is cancelled, so don't be surprised if a small mark disappears when you start a pinch.

### Jumping to an exact view

Open **Tools** and use the **World View** buttons (**Front**, **Back**, **Left**, **Right**, **Top**, **Bottom**) to jump straight to that view. If you ever get lost in the 3D world, tap **Front** to get back to a clear view.

### Other camera settings

- **Camera Mode** switches between **Perspective**, which looks natural, and **Orthographic**, where things don't shrink with distance. Orthographic is handy for lining things up.
- **Show Reference Cube** adds a cube to help you judge size and position. **Cube Size** changes how big it is.

## What is a plane in Draw!3D?

A plane is an invisible sheet in 3D space that catches your strokes.

The **tan paper** under your pen shows the plane you are drawing on. It follows your pen, so you always know where a stroke will land. To hide the paper for a clean view, turn the **Canvas** switch in the top bar off. You can still draw while it's hidden.

When you haven't picked a plane, Draw!3D places a new plane **facing the camera** each time you start drawing from a new angle:

1. From the **Front** view, draw a simple shape, like a flower.
2. Unlock Orbit and turn the view to the side. The flower is flat, standing in space.
3. Draw a second shape from this side angle. Draw!3D makes a new plane facing you, so the second shape crosses the first.
4. Turn the view again. Two flat drawings at different angles already look three-dimensional.

If you only nudge the camera slightly and are still looking at the same plane, you keep drawing on that plane.

**Tip:** a new plane is placed at the distance the camera is zoomed to. Zooming in or out before you draw changes how near or far the new plane sits. That's why a drawing can sometimes appear nearer or further away than you expected.

## How do I make a wall to draw on?

Use **Draw Straight Plane**. The line you draw is the plane's edge as seen from where you're looking, and the plane stretches straight away from you.

1. Tap **Top** under World View to look straight down.
2. Tap **Draw Straight Plane**, then draw a line across the grid. That line becomes the bottom edge of a wall standing straight up.
3. Unlock Orbit, turn the view, and draw on the new wall.

## How do I draw on a curved surface?

Use **Draw Curved Plane**. It works the same way as a straight plane, but with a curving line.

1. From the **Top** view, tap **Draw Curved Plane** and draw a curving line. This is good for a winding path, a garden border or a rounded wall.
2. Turn the view and draw on the curved surface. Your strokes follow the curve.

You can draw on either side of a curved plane: whichever side you're looking at is the side you draw on.

After drawing the curve you can resize it: drag the corner handles away from the middle to make it bigger, and drag the arrow outward to make the surface stretch further (taller, if you drew it from the top view).

## How do I draw on a sphere, cube or other 3D shape?

Use **Draw 3D Shape Plane**. The shapes are sphere, cylinder, cube, capsule, cone and pyramid.

1. Tap **Draw 3D Shape Plane** and pick a shape, for example **Sphere**.
2. Press where the shape should go and drag to size it.
3. Fine-tune the size with the arrows: the **red**, **green** and **blue** arrows stretch it in one direction, and the **white ball** in the middle sizes it evenly.
4. Tap **Place**. Once placed, the shape is locked in position.
5. Draw on the shape and orbit around it. Your strokes wrap around the shape from any side.

The erasers work on 3D shapes. Fill, Smudge and Blend currently work on flat planes only.

## How do I go back to a plane I drew on before?

Every plane you draw on is saved in the **Planes** list. Open **Layers** and switch to the **Planes** tab.

- **Draw on it again:** tap the plane in the list. The paper jumps to it, and you keep drawing on that plane even if you turn the camera.
- **Go back to drawing anywhere:** tap **Reset Camera** in Tools. New strokes will get fresh planes facing the camera again.
- **Hide it:** tap its **eye** button to hide everything drawn on that plane, which is handy for drawing behind it. Tap again to bring it back.
- **Rename it:** tap the plane's name and type a new one, like "Left wall", so it's easy to find.
- **Move it:** tap the **↕** button and drag the Left/Right, Down/Up and Away/Toward sliders. The plane and everything drawn on it move together. **Cancel** puts it back.
- **Delete it:** tap the **trash** button. This removes the plane and its drawings. **Undo** brings them back.

### Planes for solid shapes

Shapes drawn with **Depth** set above 0 become solid blocks. Each side gets its own plane in the list, so you can pick any face and draw on it or fill it. To cut a door or window into a wall, pick that wall's plane in the list, switch on **Cut out**, and draw a shape on it.

## Example: build a tiny garden

This puts everything together:

1. Tap **Top**, then use **Draw Straight Plane** to draw two lines that meet at a corner.
2. Turn the view and draw a fence on each wall.
3. Use **Draw Curved Plane** from the top for a curving flower bed edge, then draw flowers on it.
4. Add a **Sphere** 3D shape plane and draw a bush on it.
5. Unlock Orbit and slowly circle around the finished scene.

## Common questions

### Why did my stroke land somewhere strange?

It's probably on a plane you didn't expect. Turn the camera to see where it went. If you picked a plane from the Planes list, you'll keep drawing on that plane until you tap **Reset Camera**.

### Why is my new drawing much closer or further away than I wanted?

New planes are placed at the distance the camera is zoomed to. Zoom to where you want to draw first, then start drawing.

### My view keeps turning when I pan. How do I stop it?

Lock Orbit with the switch at the bottom of the screen so it reads **Orbit: Locked**.

### How do I see my drawing from another side?

Unlock Orbit and drag with two fingers, or tap one of the World View buttons.

### I'm lost in the 3D world. How do I get back?

Tap **Front** under World View in the Tools panel.

### Quick tips

- Look from the top to place walls, and from the side to draw on them.
- Name your planes as you go, so the list stays easy to use.
- Keep Orbit locked while drawing.

## Get Draw!3D and join the community

- **Download Draw!3D:** [Get it on Google Play](https://play.google.com/store/apps/details?id=com.catseagames.draw3d)
- **Video tutorials:** [Draw!3D on YouTube](https://www.youtube.com/@Draw3D-Crane)
- **Community:** share your drawings and ask questions on [r/Draw3dCommunity](https://www.reddit.com/r/Draw3dCommunity/)

[Back to all tutorials]({{ '/' | relative_url }})

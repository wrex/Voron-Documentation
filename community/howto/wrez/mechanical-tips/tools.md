---
layout: default
title: Indispensable Tools
nav_exclude: false
has_children: false
parent: Mechanical Tips
grand_parent: "How-To's"
nav_order: 1
---

# Tools

I'm fortunate enough to have accumulated a lifetime of tools. It's tempting
to prescribe expensive tools for every operation described throughout. Most
people reading this are unlikely to be retirement age, however, so it's
unreasonable to expect that everyone will have access to expensive metrology
equipment or a lathe, for example.

There are a few truly indispensable tools, however. I don't know how I'd
assemble a 3D printer without a pair of calipers, for example.

The [tools appendix](#tools) lists both _indispensable_ and merely helpful
tools. I've struggled to keep the first list as short as possible, but the
"luxury" items on the latter list will make the job much more pleasant. 

Whenever possible, I've taken pains to describe "field expedient"
techniques that don't require expensive tools or can use the printer itself as a
measuring tool.

### Standards (references for straight and flat)

In a machine shop, all precision measurements ultimately refer back to a single
reference plane: the extremely flat top of a regularly calibrated (and typically
granite) surface plate.

But nobody can build a 3D printer without **something** they can depend
on as a reference for straight and flat. The straighter and flatter, the better.

### Straightedge

First, you need something that you **know** provides a straight **line** and is
roughly as long as your longest frame member. You'll use this both to check the
straightness of individual frame members, as well as your "surface plate."

The edge of a quality metal yardstick or a good carpenter's level is probably
good enough, but even better is a precision ground rod.  

A cheap [8mm diameter x 300 mm long, hardened, chromed, and precision-ground
bearing shaft](https://www.amazon.com/ReliaBot-Hardened-Chrome-Plated-Linear/dp/B07DPF612G)
provides a decent reference for straightness. You might even have one on hand
from prior printer builds.

Whatever you use as a straightedge, use your eye with a bright light to check if
things are straight.

Let's say you are checking a 2020 aluminum extrusion for straightness. First,
find a source of bright, diffuse light. A window with sheer curtains on a
sunny day is ideal. Hold the part up against your straightedge with the light
source behind the mating edges. Look carefully, and you'll likely see areas of
darkness where the parts touch and bright areas where the part bows away from
the straightedge.

A perfectly straight part will be dark along the entire
length. You can even estimate how bent the extrusion is from the width and
brightness of any light that peeks through.

In practice, most parts aren't wavy but instead have a single bend: our
extrusion will either show a gap in the middle or the middle will touch and both
ends will bend away from the straightedge.

Beware of parts that bend away from the straightedge at the ends: changing where you hold
the parts together can affect the results. Even though the bend might be in the
middle, you'll be able to force either end against the straightedge (levering the
other end up into the air). Try not to move your hand position when examining
the gap.

With careful bending, you can often correct mild bends in an extrusion. As
should be obvious, you'll need to bend _past_ straight as there will inevitably
be some snap-back.

### Surface plate

A straightedge provides a standard reference for a straight _line_ in one dimension.

Next up is a reference for a (roughly) flat plane in two dimensions.

We only need a reasonably flat surface (say +/- 0.1mm over 400mm X 400mm) to aid
assembly.

A calibrated machinist's plate is probably overkill for most hobbyists (they are expensive and
**heavy**). Even a B grade machinist's plate is flat to within roughly 0.0006"
(0.015mm) over a couple of feet &mdash; more than 4X to 10X the precision we
require for building.

While a real surface plate (calibrated or not) is ideal, a
countertop cut-off might be more realistic (or cut-_out_ &mdash; the piece they remove for a kitchen
sink is considered scrap). Stone or solid surface (Corian) is ideal, but even a
laminate countertop should be flat enough. Even a kitchen table might suffice.

Whatever you use, you should check it with your straightedge:

Lay the straightedge on the table at random angles (at least lengthwise, across,
and on the diagonals). Shine a flashlight
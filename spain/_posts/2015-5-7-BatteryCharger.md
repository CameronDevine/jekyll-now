---
layout: spain
category: spain
title: Battery Charger
---

For Traveling through Spain I really wanted a single charger which would charge all my devices. When I bought my camera it came with a charger which would charge my camera battery or AA and AAA batteries. I have a flashlight which I am bringing to Spain which uses a CR123A battery. This is a single cell Lithium Ion battery in a similar form factor to a AA. Since the charger can charge both NiMH AAs and Li-ion camera batteries I though it should be able to charge my flashlight battery. This turned out to be the case but I had to do some soldering to make it work.

![Front of Circuit Board](/images/charger_inside_front.jpg)

After poking around inside the charger and following the circuit board traces I got enough of an understanding of how the charger worked to get it to do my bidding. It turned out a simple jumper was all that was needed. This jumper connects the negative terminal of the battery to either the other charging terminal or to ground. The charger only expects a Li-ion battery between its two charging contacts unlike NiMH which charge between a single contact and ground.

![Back of Circuit Board](/images/charger_inside_back.jpg)

While this solution works well it is not perfect. When the jumper is set for charging Li-ion batteries if a battery is placed into the wrong slot its terminals will be shorted. Overall I am happy with the way it turned out. I now have a battery charger which can charge everything I am taking to Spain and still looks almost stock.

![Finished Charger](/images/charger_outside.jpg)

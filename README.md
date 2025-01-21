[//]: # (
SPDX-FileCopyrightText: 2024 antlers <antlers@illucid.net>
SPDX-License-Identifier: CC-BY-SA-4.0
)

# Planet Card Cash-Out Mod

_"Use" a planet card while the cash-out animations play._

- Makes the "Use" button clickable, allowing players to queue one planet card.
- Gives that planet card the regular pulsing animation used for Jokers like DNA
  and Trading Card.
- Prevents the planet card from taking center-stage from the cash-out report,
  instead dissolving *in* the consumables corner. The hand-text on the left
  goes off as usual.
- Removes a 0.2s delay (hardly noticeable on higher speeds anyway).

![](demo.gif)

I was watching my SO play with a blue seal and noticed a lot of friction from
this specific delay. Now, even if it's not faster, you can hit it earlier and
the game acknowledges your pending action. I don't currently plan on doing the
same for Tarot cards, mostly because I'm happy with this as-is, but also
because they have more interactions.

It's packaged as a Lovely mod, and contains patches for lauching with or
without SteamModded. It could conflict with other mods that adjust consumable
or cash-out animations, but I haven't noticed any issues myself.

## Installation

1. Install [Lovely](https://github.com/ethangreen-dev/lovely-injector).
2. Download the [latest release](https://github.com/anter5/balatro-planet-card-cash-out-mod/releases).
3. Un-pack it.
4. Place the subfolder containing the mods files into `%appdata%\Balatro\Mods`.

## License

- Code sources and snippets are
[GPL-3.0-or-later](https://www.gnu.org/licenses/gpl-3.0.html).  
- The README and other texts are
[CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/).  
- Trivial files may be explicitly released as
[CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/legalcode).

# Additional playground icons

The playground bundles exact class-name PNGs from `30px/`. Keep these sources alongside the
existing artwork; resizing preserves aspect ratio with a maximum dimension of 30 pixels.

| Icon | Source |
| --- | --- |
| `Hand` | Exact copy of `../terraforming-mars-solarnet/assets/sidebar/preferences_cards.png`, also resized into `30px/Hand.png`. |
| `CorporationCard` | Existing `CorporationCard.png`, matching the other codebase's `assets/misc/corpCard.png`, resized into `30px/CorporationCard.png`. |
| `NormalCityTile` | Copies of `CityTile.png` and `30px/CityTile.png`. |
| `PreludeExpansion` | Copies of `Prelude1CardPack.png` and `30px/Prelude1CardPack.png`, using the existing Prelude expansion symbol. |
| `PreludeCard` | Card back cropped from the user's 2026-10-14 attachment, preserved as `sources/PreludeCard.png`. The crop is `PreludeCardBack.png` (x=14, y=462, width=598, height=426); its 30-pixel thumbnail is `30px/PreludeCard.png`. |

The existing full-size `PreludeCard.png` depicts the front and is retained for its existing uses.

## Component icons added 2026-10-16

All listed assets have a transparent 30px copy; larger source PNGs remain in this directory.

| Icons | Source |
| --- | --- |
| Adjacency, NextCardEffect, ActionUsedMarker, ColonyProduction, BioTag, PlanetaryTag, StartToken, Trade | Existing parent PNGs, resized without changing the artwork. Trade matches the local Terraforming Mars app's assets/tiles/trade.png. |
| TurmoilExpansion | Terraforming Mars app: assets/expansion_icons/expansion_icon_turmoil.png. |
| SpecialTile and all 13 named *_SpecialTile classes | Existing parent PNGs. |
| CapitalTile | White Capital artwork from page 5 of the upstream [tile reference sheet](https://github.com/terraforming-mars/terraforming-mars-assets-sources/blob/main/references/tiles.pdf), rendered inside its hexagonal cut line. Supersedes the obsolete CapitalMarker asset. |
| ScientistsUsedMarker | Identical copies of ActionUsedMarker at both sizes. |
| TradeFleet | Original vector drawing based on the user's arrow-shaped fleet reference. |
| Generation | Original restroom-style vector pictogram: a smaller child stands partly in front of the adult. |
| Community | Image-generation edit of the clear cube in ActionUsedMarker, removing the arrow and reconstructing the obscured glass. |
| NomadsMarker | Image-generation edit of Community into a solid, opaque gold cube. |
| LobbyDelegate | Image-generation edit of Delegate with a cartoony Zzzz overlay. |

Local review, source prompts, and reproducible vector/PDF rendering code are under
_local/icon-review-2026-10-16 at the site repository root.

## Abstract content category icons added 2026-10-16

| Icons | Source |
| --- | --- |
| ActiveCard, AutomatedCard, EventCard, ActionCard, BeginnerCorporation, CardFront, ColonyTile, StandardProject | Existing parent PNGs, resized to fit 30px. |
| MarsMap | ../other/mars.png, with only the black exterior background made transparent. Original RGB pixels and 1200px dimensions retained, plus its 30px version. |
| Party | Original white capsule with a gray outline, matching the proportions of the named party icons. Reproducible source: _local/icon-review-2026-10-16/draw-party.c. |
| GlobalEvent | Terraforming Mars app: assets/parties/globalEvent.png, with only exterior white made transparent. Original RGB pixels and 102 by 139 dimensions retained, plus its 30px version. |
| Award | Existing Award.png with only exterior white made transparent. Original RGB pixels and dimensions retained, plus its 30px version. |

Named concrete content does not receive 30px icons, except named parties. Special-tile
component icons remain available. Area-related category icons are deferred.

Award was already present when the site repository was created; its original artwork source
is not recorded. A matching generic Milestone source has not yet been found.

## Generic component icons added 2026-10-16

| Icons | Source |
| --- | --- |
| Tag, Tile, Resource | Existing parent PNGs, resized to fit 30px with Lanczos resampling; original artwork and transparency retained. |
| Phase | The clock geometry from the existing phase-icon SVGs in `_local/phase-icons-review/svg/`, with the phase lettering removed. Reusable source: `Phase.svg`; rendered as transparent 300px and 30px PNGs. |
| OwnedTile | Image-generation edit using `Tile.png` and the Terraforming Mars app's `assets/ma/landlord.png` as references: a tall gray X centered in the white hexagon. Replaces the blue-cube depiction; saved at 512px and 30px with transparency. |

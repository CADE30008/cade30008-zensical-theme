# Brand notice

This is the Bristol Flight Lab Zensical theme with **the Flight Lab mark
removed**. The slanted edge on the header band is kept, because it is layout
rather than mark; what has gone from `dist/assets/brand/edge-*.svg` is the
roundel, the bird and the aircraft that sat in a bulge off that diagonal, and
the "Bristol Flight Lab" wordmark beside it. The diagonal is unchanged, to the
pixel.

CADE30008 is a University of Bristol unit, not Flight Lab material, and should
not carry the Flight Lab mark.

The stylesheet is MIT licensed. What remains of the brand is not, and is not
available for reuse:

- The University of Bristol name and crest, in
  `dist/assets/brand/logo-bristol.svg` and `logo-bristol-white.svg`.
- The colour palette, including Bristol red `#B01C2E` and the accent colours.
- The visual design of the layouts: the red band, the rule, the slanted edge,
  and the placement of the crest.

Upstream is
[BristolFlightLab/flightlab-zensical-theme](https://github.com/BristolFlightLab/flightlab-zensical-theme)
at v2.0.3, whose own BRAND.md asks anyone building on it elsewhere to remove
the brand assets, change the colours and restyle the layouts. The mark is
removed here. The colours and layout are kept deliberately, because this is a
University of Bristol unit taught by Flight Lab staff, not a third party
reproducing the identity.

**`scripts/sync-brand.sh` would put the mark back.** It copies the brand assets
from flightlab-brand. Do not run it against this copy without stripping the
edge artwork again afterwards.

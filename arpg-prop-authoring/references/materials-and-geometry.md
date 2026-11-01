# Materials and geometry

Project preferences below are revisable by explicit current feedback. Numeric counts from particular past assets are not universal budgets.

## Shape, shading and construction

Use triangles for a convincing silhouette, major bends, thickness and useful contact edges. Rocks should have deliberate weathered shoulders and credible local fractures, not accidental spikes or square pedestal footprints. Avoid fixing every faceted rock by smoothing everything indiscriminately. Check mesh normals/sharp edges, silhouette and material response separately: normal detail cannot repair an outline.

Simple objects still need believable material boundaries. Bark belongs outside a log; longitudinal split wood needs continuous natural grain and torn fibres, and exposed stock ends need end grain. Align timber UV grain along the stock's length; sample a suitable plank region instead of projecting a complete board-grid atlas across each beam. Broken stump interiors are not planks. A tool needs recognizable working geometry and plausible wood/metal joins. Texture scale should agree across neighbouring props; one attractive tiling texture is not appropriate for every component of a shrine or building.

For modular openings and roof joins, inspect actual evaluated geometry and focused compatibility examples, including exposed ends and tops. Check aperture clearance and support/backing interfaces with geometry checks or rays as appropriate; bounds alone do not prove a clear opening. Where cores and facing meet, inspect their separation and avoid accidental coplanar surfaces. Report the interfaces actually tested: a few successful joins do not establish a complete building, every junction or native collision/navigation.

Inspect colour, roughness and normal detail together under unchanged light. A darker material should keep readable surface variation rather than becoming uniformly black. Use consistent channel conventions/colour spaces from the existing pipeline; verify rotated/flipped atlas normal data as well as colour/alpha alignment when applicable. Do not invent a new shader or texture system for one prop.

## Vegetation: geometry unit and texture character

For ordinary repeated vegetation, put fine leaf, blade, petal and twig detail into suitable **whole-branch sprays, multi-blade tufts or flower-head/spike groups**. Keep geometry for trunks, substantial boughs, roots, important stems/seed heads and meaningful silhouette. Do not preserve thousands of fine twig tubes or individual leaf fringes underneath a few broad cards. Detailed models can serve as bake/reference sources instead.

The user's reference images show whole leafy branch groups on a few planes, not one polygon strip for every leaf. There is no universal three-plane rule or fixed whole-tree triangle ceiling. Preserve depth/fullness from the overhead view; grass and tall lupine require different arrangements, and not every plant should become a ground decal.

**Texture repetition matters as much as card geometry.** Vary both suitable leaf samples/poses and whole branch/group compositions. Do not make a whole atlas from one conspicuously identical crop with only rotation, scale and tint changes. Reuse is allowed; keep a coherent family of shapes and material character. Useful variation includes growth sizes, bending/foreshortening, asymmetry, occasional restrained damage, believable attachment and varied outlines/gaps. Random colours or excessive damage do not establish natural variety. Distinct atlas cells should vary composition as well as their pictured leaves.

First inspect existing licensed sources for useful sample diversity. Review the atlas close-up, the complete plant and a repeated group at intended distance. If repeated vein/edge marks or regular ladders dominate, revise the source/composition before adding more mesh or enormous texture resolution. Baking an appropriate detailed source or using multiple suitable licensed samples are options, not required new services or downloads. Do not extract production textures from unknown-rights screenshots.

Fit cards to useful coverage with reasonable texture margins. When variation is needed, subcells/UV selection can add group variants within existing shared maps, at the cost of texel density. Preserve the imagery's intended aspect ratio and aligned colour/alpha/normal/roughness channels, including tangent-normal orientation; change UVs/card choices only where needed. Avoid giant empty rectangles, obvious planes, aligned combs, implausible isolated petals, excessive intersecting layers and visible dark/light filter fringes. Preserve gaps and irregular patch edges. Inspect alpha coverage and filtering at intended views; two-sided appearance, mip behaviour and shadows require relevant path checks. Blender beauty does not establish native compatibility.

Fewer triangles can trade against alpha/pixel/shadow work. Count evaluated repeated instances, preserve native gameplay headroom and measure native costs when integration is authorized. Instancing is useful but does not erase the per-visible-instance rendering work. A top-down camera reduces horizon requirements; it does not automatically remove every need for LOD, culling or texture filtering.

## Canvas and cause-based weathering

The current accepted target for worn **undyed canvas** is warm yellowish/beige cloth muted with grey-brown age, not a new white, blue-grey or cold neutral-grey material. Retain some original warmth and believable weave. Lower saturation is a tool, not the visual goal. Avoid desaturating away the material's identity, increasing apparent brightness or changing review lighting to manufacture the desired result.

Separate broad outdoor ageing from localized causes: muted exposed fibres, uneven rain/damp marks, dirt near hems/ground contacts, abrasion along working folds, fraying on stressed edges. Keep restrained variation; an identical mud band on every object is not convincing. Preserve brown lower-edge soil where appropriate, and preserve clean indoor/town variants. Do not apply this specific warm-canvas palette to every dyed fabric or unrelated material.

Compare clean/baseline and weathered versions under the same light. Judge whether it reads as the same material with a history of use, not simply a hue/saturation operation that passed a numeric test.

Apply the selected shared treatment through a versioned, repeat-safe recipe: applying the same version twice must not compound ageing. Preserve weave, clean variants and existing ingredient-local dirt/wear frames and masks. Keep dark-cloth identity separate from the response selected for pale canvas; a numerical recipe is not a universal cloth rule.

# Educational games

Small browser-based learning tools published with GitHub Pages.

- Public URL: https://jahooker.github.io/educational-games/
- VSEPR Studio: https://jahooker.github.io/educational-games/vsepr-studio.html

## VSEPR Studio

`vsepr-studio.html` is a VSEPR geometry tool for exploring AXE patterns and example molecules.

### Current design

- The template grid displays AXE formulae.
- Once an AXE formula is selected, matching molecule examples are shown.
- By default, the viewport uses generic `A` and `X` atom labels.
- Selecting an example molecule assigns `A` and `X` to the appropriate elements.
- Users can clear the element identities to return to generic `A` and `X` labels.
- Changing the AXE formula with the grid or X/E controls clears any assigned element identities.
- The viewport shows the AXE formula in the top-left corner.
- The viewport shows the chemical formula in the top-right corner once an example molecule has been selected.
- The `S = m + n` panel is inside the viewport as an interactive overlay.
- The `S = m + n` overlay has no surrounding box.
- `S` denotes the steric number.
- `m` denotes the number of surrounding atoms.
- `n` denotes the number of non-bonding electron domains.
- The X/E increment and decrement controls preserve the labels of the central and surrounding atoms.
- Below the viewport, there is an explanation of the molecular geometry, including expected bond angle and polarity information.

### Examples

The VSEPR examples currently cover simple molecules up to `S = 7`:

- `CO2`, `BF3`, `SO2`
- `CH4`, `NH3`, `H2O`
- `PCl5`, `SF4`, `ClF3`, `XeF2`
- `SF6`, `BrF5`, `XeF4`
- `IF7`, `XeF6`

Avoid charged molecules unless there is a clear reason to add them.

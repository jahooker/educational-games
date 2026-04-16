# AGENTS.md

## Git

- Remote: `https://github.com/jahooker/educational-games.git`
- Public URL: `https://jahooker.github.io/educational-games/`

## Preferences

- Be concise.
- Be precise.
- Be consistent.

## VSEPR studio 

- `vsepr-studio.html`

### Recent design decisions

- The viewport shows the chemical formula in the top-left corner.
- The viewport shows the AXE formula in the top-right corner.
- The `S = X + E` panel is inside the viewport as an interactive overlay.
- The `S = X + E` overlay has no surrounding box.
- `S` denotes the *steric number*.
- `X` denotes *surrounding atoms*.
- `E` denotes *non-bonding electron domains*.
- The X/E increment/decrement controls preserve the labels of the central and surrounding atoms.
- Below the viewport, there is an explanation of the molecular geometry, including expected bond angle and polarity information.

### Existing content and examples

- The VSEPR presets currently cover some simple examples (up to `S = 7`):

- `CO2`, `BF3`, `SO2`
- `CH4`, `NH3`, `H2O`
- `PCl5`, `SF4`, `ClF3`, `XeF2`
- `SF6`, `BrF5`, `XeF4`
- `IF7`, `XeF6`

- Try to avoid charged molecules.

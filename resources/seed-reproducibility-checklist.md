# Seed and Reproducibility Checklist

## Randomness
- [ ] Seed is explicit and stored with the output.
- [ ] Both random and noise generators are initialized from the same seed.
- [ ] No unseeded randomness enters the rendering path.
- [ ] Random calls occur in a deterministic order.
- [ ] Time, browser state, and external data do not silently alter static output.

## Parameter state
- [ ] Parameter defaults are documented.
- [ ] Parameter values are serialized with the seed.
- [ ] Parameter changes trigger the correct redraw or regeneration.
- [ ] Reset restores the documented defaults.
- [ ] Invalid values are bounded or rejected.

## Verification
- [ ] The same seed and parameters reproduce the same output.
- [ ] A second seed produces a valid variation.
- [ ] Exported PNG dimensions and file names are correct.
- [ ] Browser refresh does not change a supposedly fixed composition.
- [ ] Viewer controls work by keyboard as well as pointer.
- [ ] Heavy scenes remain within the agreed memory and frame-time budget.

Record seed, parameter JSON, generator version, and output dimensions together.

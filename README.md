# The Abstraction Atlas

*for computational neuroscience* · NeuroAI Explainers · Plate I

**Live site:** https://mrio.github.io/AbstractionAtlas/

The Abstraction Atlas charts the principal simplifications by which computational neuroscience has learned to describe neural tissue, from ion channels to networks of areas, together with the passages that connect them.

Each model on the map is a deliberate omission, and each edge records what a simplification retains, what it forfeits, and the conditions under which its conclusions remain trustworthy. Enter at whichever node you happen to arrive, then move inward towards detail or outward towards parsimony, following the dashed links wherever plasticity, modulation or noise alter the picture.

## Reading the plate

- **Edges:** simplification, composition, side branch, and modulators (shown on selection)
- **Confidence marks:** ● established · ◐ likely · ○ unverified · † disputed
- **Views:** Overview and Detail, with pan and zoom
- **Prints:** *Plate* (grey paper, black ink) and *Cyanotype* (light blue paper, deep blue ink)

Selecting a node opens its reading card, which links to a full explainer plate.

## Plates

| # | Topic |
|---|---|
| 02 | Stochastic channel gating |
| 03 | Single channel to macroscopic conductance |
| 04 | Passive cable theory |
| 05 | Isopotential approximation |
| 06 | Conductance-based neuron model |
| 07 | Timescale separation |
| 08 | Phase-plane analysis of excitability |
| 09 | Threshold and reset |
| 10 | Leaky integrate-and-fire neuron |
| 11 | Synaptic coupling |
| 12 | Balanced excitatory–inhibitory network |
| 13 | Mean-field approximation |
| 14 | Excitatory–inhibitory rate model |
| 15 | Laminar population decomposition |
| 16 | Laminar cortical microcircuit |
| 17 | Lumped population approximation |
| 18 | Neural mass model of a cortical column |
| 19 | Continuum limit |
| 20 | Neural field equations |
| 21 | Brain parcellation |
| 22 | Connectome-based brain network model |
| 23 | Weighted sum and nonlinearity |
| 24 | Artificial neural networks |
| 25 | Binary units and symmetric coupling |
| 26 | Attractor networks and associative memory |
| 27 | Phase reduction |
| 28 | Coupled phase oscillators |
| 29 | Graph abstraction |
| 30 | Connectivity graphs |
| 31 | Forward problem |
| 32 | Forward models of neural signals |
| 33 | Spike-timing-dependent plasticity |
| 34 | Normalised Hebbian learning and principal components |
| 35 | Synaptic depression and facilitation |
| 36 | Neuromodulatory gain control |
| 37 | Phase-dependent gating |
| 38 | Homeostatic synaptic scaling |
| 39 | Noise-enhanced signal detection |

## Structure

```
index.html     the atlas map (landing page)
plates/        one self-contained HTML explainer per model
```

Everything is static HTML, CSS and JavaScript with no build step. To view locally, open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server
```

Part of [NeuroAI Explainers](https://mrio.github.io/NeuroAI_explainers/).

# Local Animal Stage public connectome packages

Static, revisioned connectome packages used by the Public Web build of Local Animal Qorvyx Stage. This repository contains data files and attribution only; the game source stays in the private `close-fly` repository.

The app fetches a revision only after the player accepts the displayed dataset terms. The included revision is `3fb8f19550526878`; its `inventory.json` records every package file's exact byte size and SHA-256 digest. The client rejects files that fail either check.

## Data and attribution

- **MaleCNS v1.0, adult male fruit fly** — collaboration between FlyEM at HHMI Janelia Research Campus, the University of Cambridge, the MRC Laboratory of Molecular Biology, and Google Research. Dataset source and terms: <https://male-cns.janelia.org/>. The Male CNS dataset is licensed CC BY 4.0.
- **Ciona intestinalis larva** — Ryan, K., Lu, Z. & Meinertzhagen, I. A. (2016), “The CNS connectome of a tadpole larva of *Ciona intestinalis* (L.) highlights sidedness in the brain of a chordate sibling,” *eLife* 5:e16962, <https://doi.org/10.7554/eLife.16962>. The article and source data are licensed CC BY 4.0.

Each original dataset retains its own attribution and licence. Reusers must credit the relevant source above and comply with CC BY 4.0: <https://creativecommons.org/licenses/by/4.0/>.

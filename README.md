# Simulated Mural-Damage Masks

This repository provides a small simulated mural-damage mask set for supplementary evaluation of mural image inpainting methods.

The mask set contains three types of binary masks:

1. Fragmented peeling masks
2. Crack-network masks
3. Speckled erosion masks

Each mask is a binary image, where white pixels represent missing/damaged regions and black pixels represent valid regions.

The dataset includes:
- 200 training masks and 50 test masks for fragmented peeling
- 200 training masks and 50 test masks for crack-network damage
- 200 training masks and 50 test masks for speckled erosion

In our paper, only the test split is used for supplementary evaluation. These masks are not used to train or fine-tune the proposed method or any compared baseline.

# DARLS
## Setup

1. Get HF_TOKEN from huggingface.co/
2. Pre-download Mistral weights (avoids XetHub network issues on cluster):
   `HF_HUB_DISABLE_XET=1 hf download mistralai/Mistral-7B-v0.1 --token YOUR_TOKEN --max-workers 1`
3. Fill in HF_TOKEN in Cell 2
4. Change DATASET_SOURCE, SELECTION_METHOD, BUDGET_M in Cell 2
5. Run all cells top to bottom

## Conditions to run (30 total)
See condition table in notebook header.

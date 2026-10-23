# post-training-log

Learning log for LLM post-training (SFT, RLHF, DPO, …). Notes live in [`notes/`](notes/).

## Setup (macOS, Apple Silicon)

```bash
uv venv --python 3.12 .venv
uv pip install --python .venv/bin/python torch torchvision jupyterlab ipykernel
.venv/bin/python -c "import torch; print(torch.backends.mps.is_available())"
.venv/bin/jupyter lab
```

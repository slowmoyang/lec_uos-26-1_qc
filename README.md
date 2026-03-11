# Lec_QC_UOS-26-1


## Recipies

### Install `uv`
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```
See https://docs.astral.sh/uv/getting-started/installation/ for more details.

### Install dependencies
```bash
uv sync
```

### Add the kernel to Jupyter

```bash
uv run ipython kernel install --user --name lec_qc_uos-26-1
```

### Launch Jupyter Lab

```bash
uv run jupyter lab --port <PORT>
```

If you are working on a remote server, you need to set up port forwarding
```bash
ssh -L <LOCAL_PORT>:localhost:<PORT> <USER>@<HOST>
```

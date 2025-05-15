fork of https://github.com/nerlfield/wild-gaussian-splatting

# Wild Gaussian Splatting

<video loop="loop" autoplay="autoplay" muted>
  <source src="data/assets/results.mp4.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMHVxYjRsZXd3dHlrZnljNnVvaWx5cDdyNjJmMjc0YmhpdmppcGp1cyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/jBxJfbzw9NqUeASrOo/giphy-downsized-large.gif"/>


## Setup

Install uv
```bash
pip install uv
```

Build environment
```bash
uv sync
# If errors out, follow instructions: uv pip install torch && uv sync --no-build-isolation
```

Download checkpoints:
```bash
./download_checkpoints.sh
```

Compile RoPe kernels (Optional):
```bash
./compile_rope.sh
```

Launch JupyterLab
```bash
uv run jupyter lab
```

Follow instructions in the notebooks/ folder

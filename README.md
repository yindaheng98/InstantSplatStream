# InstantSplatFlow

Fast volumetric video reconstruction, just like InstantSplat

## Install

### Requirements

Install Pytorch and torchvision following the official guideline: [pytorch.org](https://pytorch.org/)

Install Pillow, numpy and tqdm
```sh
pip install Pillow numpy tqdm
pip install --upgrade git+https://github.com/yindaheng98/gaussian-splatting.git@master
pip install --upgrade git+https://github.com/yindaheng98/InstantSplat.git@main
pip install --upgrade git+https://github.com/facebookresearch/co-tracker.git@main
```

### Pip Install

```shell
pip install --upgrade git+https://github.com/yindaheng98/InstantSplatStream.git@main
```

### Local Install

```shell
git clone https://github.com/yindaheng98/InstantSplatStream --recursive
cd InstantSplatStream
pip install --target . --upgrade .
```

## Download pth

```shell
wget -P checkpoints https://huggingface.co/16lemoing/dot/resolve/main/cvo_raft_patch_8.pth
wget -P checkpoints https://huggingface.co/16lemoing/dot/resolve/main/movi_f_raft_patch_4_alpha.pth
wget -P checkpoints https://huggingface.co/16lemoing/dot/resolve/main/movi_f_cotracker_patch_4_wind_8.pth
wget -P checkpoints https://huggingface.co/16lemoing/dot/resolve/main/movi_f_cotracker2_patch_4_wind_8.pth
wget -P checkpoints https://huggingface.co/16lemoing/dot/resolve/main/panning_movi_e_tapir.pth
wget -P checkpoints https://huggingface.co/16lemoing/dot/resolve/main/panning_movi_e_plus_bootstapir.pth
wget -P checkpoints https://huggingface.co/facebook/cotracker3/resolve/main/scaled_offline.pth
```
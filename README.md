# CR-CDANet

Official PyTorch implementation of **CR-CDANet**.

**Cycle-Refined Cross-Modal Diffusion Based Domain Adaptation Network for Multimodal Remote Sensing Images Change Detection**

## Requirements

```bash
pip install -r requirements.txt
```

For PyTorch with CUDA 11.8, you can install it by:

```bash
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```

## Run

```bash
python demo/run_pipeline.py --start_loop 0
```

## Project Structure

```text
CR-CDANet/
├── demo/
├── dataloader/
├── diffusion/
├── change_detection/
├── modelnet/
├── transfer_learning/
├── requirements.txt
└── README.md
```

## Citation

The citation will be updated after publication.

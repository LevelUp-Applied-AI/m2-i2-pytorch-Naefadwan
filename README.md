[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YUvA8hIt)
# Integration 2 — PyTorch: Housing Price Prediction

**Module 2 — Programming for AI & Data Science**

See the [Module 2 Integration Task Guide](https://levelup-applied-ai.github.io/aispire-14005-pages/modules/module-2/learner/integration-guide) for full instructions.

---

## Quick Reference

**File to complete:** `train.py`

**Install PyTorch before running:**
```bash
pip install torch --index-url https://download.pytorch.org/whl/cpu
```

**Branch:** `integration-2/pytorch`

**Submit:** PR URL → TalentLMS Unit 8 text field
# PyTorch Housing Price Prediction

## What the Model Predicts
The model predicts apartment prices in Jordan (price_jod).

Input features:
- area_sqm
- bedrooms
- floor
- age_years
- distance_to_center_km

## Training Configuration
- Epochs: 100
- Optimizer: Adam
- Learning Rate: 0.01
- Loss Function: Mean Squared Error (MSE)

## Training Outcome
The loss decreased consistently during training.

Example:
- Epoch 0 Loss: ~ very high
- Epoch 50 Loss: significantly lower
- Epoch 100 Loss: much lower

## Observation
Loss decreased rapidly in the first few epochs, then gradually stabilized, indicating the model learned the main patterns early.
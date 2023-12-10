# Waste Classification
Convolutional Neural Network - Final Project

## Important Links
Documentation
- https://docs.google.com/document/d/1-ePLMW-txVX3416LHrMvl3WkZsmC1jGtQvurWJwkkd4/edit

Presentation
- https://www.canva.com/design/DAF2YtdDDkk/BDS-_qGq0GKnuWjRcfP-0w/edit

## ChangeLog: VGG Model
- Base model; no adjustments
  - 50min/epoch

- Tweaks
  - Image Size -> 32x32
  - Added mixed precision (float32)
  - Added callback (early stopping)
  - Added callback (model checkpoint)
  - Added MaxPooling (redacted)
  - Added Global Average Pooling 2D
  - Added Dense Layer 

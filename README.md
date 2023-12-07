# Waste Classification
Convolutional Neural Network - Final Project

## Important Links
Documentation
- https://docs.google.com/document/d/1-ePLMW-txVX3416LHrMvl3WkZsmC1jGtQvurWJwkkd4/edit

Presentation
- ...

## Added VGG Model
- Base model; no adjustments
  - 50min/epoch
## ChangeLog
- Add dataset to directory
- Add Model Comparison folder
  - metric graphs, loss graphs, and model overview
- Add Test Prediction folder
  - imgs identical to og model
- Waste_Classification
  - adjust img sizes (224x224 -> 32x32)
    - a:87%/va:90% (10s/epoch)
  - 64x64
    - a:89%/va:89% (25s/epoch)
  - update prediction img location
- Add img filtering 
- Add sample image visualization
- Updated training and validation sets from DirectoryIterators to TensorFlow data sets
  - Difference between a. and v.a. is more significant (~5%-6%)
- Add mixed precision
  - 32x32 -> 6s/epoch
  - 64x64 -> 20s/epoch

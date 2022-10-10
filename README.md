# Speech-Recognition
Build a model to detect phonemes in speech recordings. 

Reached 86% accuracy.
To run just "Run all."
To load existing model uncomment block under Testing and submission.

# Experiments:

Context sizes: 0-30

Layer widths: 256-2048

Depths: 3-12 layers

Shapes: Cylindrical, Pyramid, Pencil-like

Schedulers: ReduceLRonPlateau, MultistepLR

Optimizers: Adam, AdamW

Data: Cepstral normalization

Activations: RELU, GELU

Batch Normalization: 0-0.3, alternating layers or full

Epochs: 10-50

Batch Sizes: 1024, 2048

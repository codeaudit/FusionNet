Fusion Net
==========


Implementation of [FusionNet](https://openreview.net/forum?id=BJIgi_eCZ) for [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/)


Todo
----

- [x] Basic Model
- [ ] Top question word tuning
- [ ] Dropout
    - [x] Embedding dropout
    - [x] LSTM dropouts
    - [ ] Attention dropouts
    - [ ] Linear transform dropouts
- [ ] Masking
- [ ] Disk caching
- [ ] Optimizer
- [ ] Data Preparation with Spacy
- [ ] Tensorboard
- [ ] Single model
- [ ] Ensemble
- [ ] Demo


Performance
-----------

Tag    |   F1  |   EM
-------|-------|----------



Notes
-----

- Dropout details are provided at [openreview](https://openreview.net/forum?id=BJIgi_eCZ&noteId=SJftaCpyM)
- Attention dimensions are confirmed to be 250 for all fusions

# Implementation

The first step of every research is to repeat the baseline and get competitive results (definition of what competitive means may vary depending on domain, future plans and computational resources). 

For DL projects I suggest using [PyTorch Template for DL projects](https://github.com/Blinorot/pytorch_project_template/tree/main) by Petr Grinber. As a reference you can check out `example/image-classification` branch or one of my projects: [DeepFake Detection](https://github.com/runtime57/deepfake_detection) or [Speech Enhancement](https://github.com/runtime57/speech_enhancement).

The order of implementation should be as stated:

1. Datasets

    Parsing, storing, generating a batch in `src/datasets` and `collate.py`

2. Model

    Implement the baseline in `src/models`

3. Loss

    Implement the loss function in `src/loss`

4. Metrics

    Implement basic metrics you need in `src/models`. Make sure you work with correct dimensions

Remember that in this template Hydra config management is used so you have to add config for each new subject you create. Add configs on time in the end of every step. If you are having trouble with it, check out the examples above.

After completing steps above you are good to go!
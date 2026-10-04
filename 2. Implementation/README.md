# Implementation

The first step in any research project is to reproduce the baseline and achieve competitive results. The definition of "competitive" may vary depending on the domain, future plans, and available computational resources.

For DL projects, I suggest using the [PyTorch Template for DL projects](https://github.com/Blinorot/pytorch_project_template/tree/main) by Petr Grinber. For reference, you can check out the `example/image-classification` branch or one of my projects: [DeepFake Detection](https://github.com/runtime57/deepfake_detection) or [Speech Enhancement](https://github.com/runtime57/speech_enhancement).

Follow this implementation order:

1. **Datasets**

   Parse and store data, and generate batches in `src/datasets` and `collate.py`.

2. **Model**

   Implement the baseline in `src/models`.

3. **Loss**

   Implement the loss function in `src/loss`.

4. **Metrics**

   Implement the basic metrics you need in `src/models`. Make sure you use the correct dimensions.

Remember that this template uses Hydra for configuration management, so you need to add a config for each new component you create. Add the relevant configs at the end of each step. If you have trouble with this, check out the examples above.

After completing the steps above, you are good to go!

---

To make working with this template easier, I suggest starting with something small and simple instead of trying to run a Transformer architecture right away.

Clone the template to your machine, then open the `example/image-classification` branch in the GitHub web interface and try to reproduce its results by making changes in the suggested order. Keep the completed GitHub version open alongside your local copy, reproduce the code, and modify the configs locally. Once you are done, you will have a complete understanding of the code and a clear workflow for the full project. Then we can discuss the roles.

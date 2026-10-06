# Experiments

### For the Research Project

1. Define the main research question.
2. Decide what result will count as success.
3. Choose the baseline, dataset, and main metric.

---

### For Each Experiment

1. State a clear hypothesis. What exactly do you want to test?
2. Decide what result you expect. How do you think the metrics and overall performance will change?
3. Plan an experiment that tests only this hypothesis.
4. Make the change, run the experiment, and record the results.
5. Write a short note about whether the results matched your expectations. This can help you find new ideas and will be very useful when you write the final paper.

> **Important:** Never run an experiment without knowing why you are running it. At the very least, write down what you are unsure about and what you want to learn.

You will often have several good ideas that may improve performance. Do not test them all at once. Change one thing at a time so that you know what caused the improvement.

> Tip: Clear notes about your experiments will help you understand the results, so writing them is not a waste of time.

---

### What to Do

1. **Overfit a single batch.** Train the model on one batch and make sure the loss goes down. Start with the simplest setup, then make it more complex step by step until your training pipeline works correctly.

2. **Reproduce the baseline.** Follow the authors' pipeline and try to reproduce their results. It is okay to make necessary changes, for example, if the original training process requires more computing resources than you have. Make sure you record every change.

3. **Run your own experiments.** Once you have a reliable baseline, use the steps above to plan and run your experiments.

To recreate the benchmark results shared in the paper, please run the files in the following order, after downloading the raw audio:
1. preprocess.ipynb (This extracts the vocal-only data along with the features used in all experiments and VGGish embeddings)
2. 3class_results/train_test_split_3class.ipynb 
3. 6class_results/train_test_split_6class.ipynb

After running the above files, you can re-create the results for the different feature sets found in the 3class_results and 6class_results folders
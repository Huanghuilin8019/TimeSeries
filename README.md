## To run:

To download the dataset and preprocess the data:
1. python preprocess_elect.py
Start training:
2. python train.py
If you want to perform ancestral sampling,
2. python train.py --sampling
If you do not want to do normalization during evaluation,
2. python train.py --relative-metrics
Evaluate a set of saved model weights:
3. python evaluate.py
Perform hyperparameter search:
4. python search_params.py
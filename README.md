# CSE256_FA24_Final_Project
### File description:
*   `data/`: contains the vanilla and augmented SQuAD datasets
*   `data/Data_augmentation.ipynb`: fetches the SQuAD datasets and augment it, takes very long time to run.
*   `models/`: contains the model trained with vanilla and augmented datasets
*   `Training.ipynb`: trains the model without augmented datasets
*   `Training_augmented.ipynb`: continue trains the model with augmented datasets
*   `Inference.ipynb`: try examples with the 2 trained models

*   The sequence to run the notebooks should be: 
*   `Data_augmentation.ipynb` - `Training.ipynb` - `Training_augmented.ipynb` - `Inference.ipynb`

*   For time concern, just run the examples with `Inference.ipynb` is recommended.

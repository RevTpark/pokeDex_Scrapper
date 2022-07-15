## Scrapper for PokeDex
- This repo contains all the code used to Scrap data for my [PokeDex Project](https://github.com/RevTpark/pokeDex). 
- Scrapped Data of pokemon like name, dex_id, image, etc to provide information for my database on main project.
- Scrapped Data of Types, their weakness and strengths for database.
- Scrapped gifs and converted to images frame by frame to make dataset for image classification model used in main project.
- Scrapped descriptions for text classification model used in main project.

## Machine Learning 
- Added code used to train image classification model as well as text classification model.
- For image classification, used CNN and provided a moderate strength dataset. Each pokemon had about 100-150 distinct images and model was trained to classify the first 151 pokemon. The accuracy when tested with unseen images was around 93% which means it predicts a wrong result 1 out of 10 images. This was the best model trained out of the dataset and conditions provided.
- For text classification, used pre-trained model BERT that is used to identify english case insensitive and also used RNN for mutli-label classification. Dataset contained about 40-60 descriptions of each pokemon. The accuracy when tested with unseen descriptions was around 99% which meant it predicts a wrong result 1 out of 151 description. This was best model trained as it never got to 0 out of 151. 

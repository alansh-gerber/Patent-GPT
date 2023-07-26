# Patent-GPT

I created two example models of a generative text program that was trained on a dataset of 1300 patent titles, and fine-tuned on a further 1050. 
The two datasets are attached to this project but they can be replaced and the model can be trained on any other text a user wants. Additionally, they can be added to in order to create a stronger model.

The datasets was based off of patents approved on June 30th, 2022. These titles were compiled onto a textfile and used as the dataset for the model. The model itself was built using the tutorial outlined in https://youtu.be/kCc8FmEb1nY by Andrej Karpathy. This model is a very simpe example of how we can create a model addressing a very specific niche such as patent applications. I fine-tuned the model as well to create slightly more understandable output, however, creating a more powerful model that creates outputs in understandable English is beyond the computing ability of my device and datasets.

The purpose of this project is to demonstrate what is capable under a extremely basic language model, and to also showcase how results vary before and after fine-tuning.

I am attaching three versions of this model:
1. The first version is your regular model as would be built in the tutorial mentioned above, with no finetuning or other processes done on it.
2. The second version is a program where the user can input data such as "PIZZA MACHINE EMPLOYING FAIRYDUST", and the model attempts to complete the statement to make a title. This is before finetuning.
3. The third version is a finetuned model that can accept user input and create written out answers.

The input texts order can be varied or completely swapped out using whatever the user desires. Patents were just an example of a personal passion.

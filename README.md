# Patent-GPT

I created a not fine-tuned model of a generative model that was trained on a dataset of 1050 patent titles.
The dataset was based off of 1050 patents approved on June 30th, 2022. These titles were compiled onto a textfile and used as the dataset for the model. The model itself was built using the tutorial outlined in https://youtu.be/kCc8FmEb1nY by Andrej Karpathy. This model is a very simpe example of how we can create a model addressing a very specific niche such as patent applications, however, it would first need significantly more work done for the fine-tuning process. 

I am attaching two versions of this model:
1. The first version is your regular model as would be built in the tutorial mentioned above.
2. The second version is a program where the user can input data such as "PIZZA MACHINE EMPLOYING FAIRYDUST", and the model attempts to complete the statement to make a title.

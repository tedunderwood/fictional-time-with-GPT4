Estimating fictional time with large language models
====================================================

A casual replication of part of ["Why Literary Time is Measured in Minutes"](https://github.com/tedunderwood/moments) using ChatGPT and GPT-4 through the OpenAI API.

Please note this is casual work for a blog post, and is currently documented lightly. Also a couple parts are not done as carefully as I would for an article: e.g. in the bag of words solution I select features for test and training at once, pooling both sets, which is not good practice if you're being careful.

The API interactions are in ```GetTimes.ipynb``` (which uses Chat) and ```GetTimesGPT4.ipynb``` (GPT-4).

The output of those scripts goes to ```output2.tsv``` (for Chat) and ```outputGPT4.tsv``` (for GPT-4). There you can see the original passages of fiction, plus the Assistant's responses to them, and times estimated by both the human reader and the model.

I'll document this a little more carefully later today.


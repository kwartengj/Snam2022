# Misogynoir: Challenges in Detecting Intersectional Hate
Repository for Kwarteng, Joseph; Coppolino Perfumi, Serena; Farrell, Tracie and Fernandez, Miriam. 2022. "Misogynoir: Challenges in Detecting Intersectional Hate" SNAM 2022.
<!-- You read the paper [here](https://dl.acm.org/doi/10.1145/3487351.3488342) -->
There are several automated detection methods for both hate speech, misogyny and racism. However, to our knowledge, no automated misogynoir detection systems have been proposed. This experiment will evaluate high-performing automated hate speech detection systems of related types of hate on a misogynoir dataset to address their effectiveness. The objective is to acquire insight into the shortcomings and strengths of existing models. In this experiment we explored two prominent state-of-the-art hate speech detection classifiers: HateSonar and Google’s Perspective API.

## HateSonar
HateSonar is the hate speech detection library for Python. HateSonar allows you to detect hate speech and offensive language in text, without the need for training. We are employing HateSonar to filter the dataset to find instances of offensive language and hate speechs. Ref: https://github.com/Hironsan/HateSonar

## Google's Perpective API
Perspective is a free API that uses machine learning to identify comments, making it easier to host better conversations online. Perspective uses machine learning models to identify abusive comments. The models score a phrase based on the perceived impact the text may have in a conversation. Developers and publishers can use this score to give feedback to commenters, help moderators more easily review comments, or help readers filter out language.

Perspective models provide scores for several different attributes. In addition to the flagship Toxicity attribute, here are some of the other attributes Perspective can provide scores for:

Severe Toxicity Insult Profanity Identity attack Threat Sexually explicit To learn more about our ongoing research and experimental models, visit our Developers site: https://www.perspectiveapi.com/research/

## 

You can find the datasets used for this study in the datasets folder.

To run the jupyter file, you must "rehydrate" the tweet IDs in the datasets into Tweets using the Twitter API.

Note: You'll need to register for an API key to use Perspective API.

<!-- WARNING: The data and lexicons contain content that is racist, sexist and offensive in many other ways. -->

<!-- You can find our labelled data in the data directory and the lexicons in the lexicons directory  -->

# Fake-News-Detection-Project-NLP
False news, also known as unwanted news, false stories, misconceptions or fraudulent stories, types of stories that contain deliberate information or frauds that are spread through traditional media (print and broadcast) or online media. Digital news has revived and increased the use of fake news, or yellow journalism. These stories are often referred to as information that is not in the media but sometimes finds its way into the mainstream media as well.

## Problem description:
At Bytedance, we have created a large-scale database to store existing fake news articles. Any new article must go through a test on the truthfulness of content before being published. We conduct matching between the new article and the articles in the database. Articles identified as containing fake news will be withdrawn after human verification. The accuracy and efficiency of the process, therefore, becomes crucial for us to make the platform safe, reliable, and healthy.

## Recommended Project Steps & Guidelines:
1. Prepare the data: You’re provided with two excel dataset, first level them and merge those twodata into one.
2. Clean the data: Clean the data, that is, remove the duplicated news articles, remove specialcharacters, numbers etc., correct the spellings of words.
3. Conduct EDA (Exploratory Data Analysis) on the cleaned Data: Perform Unigram, Bigram andTrigram analysis on both real and fake news. Create wordcloud on both data based on the subject.Summarize the words and explore the data and then decide your strategy. Make note of anyimportant assumptions that you make.
4. Convert the text data: You have to transform each news article into a numerical representation tocreate a machine learning model. For example, if we have defined our dictionary to have thefollowing words(predictors) {This, is, the, not, awesome, bad, basketball}, and we wanted totransform the text “This is awesome” into a numerical representation, we would have the followingnumerical representation of that text : (1, 1, 0, 0, 1, 0, 0).
5. Develop and Validate Samples: Divide converted data into 2 parts: Development Sample (70%) &Validation Sample (30%). Build your analysis model using the Development Sample, and validate iton the validation sample and then predict on test sample. You can use neural network to create amodel.
6. Improving model accuracy: Perform various iterations by eliminating or adding thevariables(words) to see if the model accuracy is improving or not.

## Variable Description :
You’re provided with two excel files named as Real_News and Fake_news. In both the files you will find -
* Title: The title of the news article.
* News_Text: Contains the detail of news article.
* Subject: The topic of the article

![1_RGVPc-MT0q_DCHCavFRHvA](https://user-images.githubusercontent.com/88396377/147363903-b776d906-ec18-44d9-bd00-7ed1af0fb659.jpeg)

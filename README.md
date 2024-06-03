# Research-on-the-Construction-of-Chinese-Multimodal-Metaphor-Corpus-and-Sentiment-Classification
We create a new Chinese multimodal metaphor corpus, which includes 8089 text image pair samples. 
We manually annotated at a fine-grained level whether the data is a metaphor, as well as the emotions of joy, anger, sadness, fear, shock, and neutrality triggered by metaphors. 
Unlike the previous emotional annotations of "positive, negative, and neutral" metaphors both domestically and internationally, this study attempts for the first time to provide fine-grained emotional annotations for multimodal metaphors.
Our images and data can be downloaded at the following link [DataAll](https://www.kaggle.com/datasets/liuyuxi718/chinese-multimodal-metaphor-and-sentiment-corpus)

## Example Instance
**The multimodal metaphor and sentiment classification example in our dataset is shown in the following figure：**
.<div align='center'><img src='example/example.png' width="745" height="416"></div>
+ Text in the picture:Ocean Its Paradise Not a garbage dump
The turtle and garbage in the picture form a metaphor, with "turtle" appearing in the image mode and "garbage" appearing in both the image and text modes.The picture and text express sympathy for sea turtles and sadness about ocean pollution as a whole.


## Annotation Guideline
**We provide annotators with annotation guidelines.The specific labeling steps are as follows:**
+ Step 1: Observe the image and text to identify all the objects contained in the image and text.
+ Step 2: Determine whether there is a conflict or inconsistency between the identified objects that does not conform to common sense. If there is a conflict, label the image text pair as a metaphor, otherwise it is a non metaphor.

**The classification and explanation of sentiments are as follows：**
+ Joy: Joy includes feelings of joy, happiness, optimism, and varying degrees of joy, such as ecstasy and relaxation. It also includes love, sincere emotions towards people or things, positive recognition and friendly emotions, as well as trust, acceptance, and appreciation.
+ Anger: Angry emotions that arise when injustice or bad things occur, including irritability and anger.
+ Sorrow: The emotional state of sadness, usually used to describe the psychological state experienced when facing negative emotions such as loss and pain. This emotional state is usually characterized by feelings of depression and sadness.
+ Fear: Fear conveys negative feelings that arise when facing danger or encountering frightening things, including worry, anxiety, and panic, as well as feelings of disgust and resistance.
+ Surprise: The emotion of surprise, often triggered by sudden or unexpected events, includes both surprise and surprise.
+ Neutral: Does not evoke any emotions.

## Data Format
The file data_all.xlsx contains all the data we have annotated, including images and the text and annotation items in the images. The specific instructions are as follows:
| Key                 |                                    Value                                    |
|---------------------|:---------------------------------------------------------------------------:|
| `Pic_id`            |                The address of the picture to be identified                  |
| `Text`            |                Text in the picture                  |
| `MetaphorOccurrence`|           Metaphorical judgment (0: non-metaphorical; 1: Metaphor)          |
| `SentimentCategories`|      Type of sentiment of the picture and text( 1:joy;2:anger;3:sad;4:fear;5:surprise;6:meutral)       |

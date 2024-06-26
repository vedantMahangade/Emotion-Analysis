## Emotion-Analysis
Emotion analysis and recognition in text using Support Vector Machines (SVM) for classification and K-Means clustering for pattern discovery

### Dataset Description:

This is the EmotionLines dataset which contains labeled emotion on every utterance in dialogues from Friends TV scripts and EmotionPush chat logs.

Data Information:
The number of dialogues in three split sets(train, dev, test) for each source are 720, 80, 200 respectively.
More details could be found in the paper "EmotionLines".

Raw Annotation:
Every utterance in both datasets containans a "annotation" string which represents the raw annotations by 5 annotators.
The emotion order of the annnotation string is [neutral, joy, sadness, fear, anger, surprise, disgust]
The detail of how we define non-neutral emotion can be found in the paper.
Examples:
"annotation": "2003000" -> "emotion": "fear"
"annotation": "0500000" -> "emotion": "joy"
"annotation": "2011010" -> "emotion": "non-neutral"

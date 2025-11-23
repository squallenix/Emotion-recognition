In this study, for uni-modal models three modalities speech,
image, and text were utilized to perform emotion recognition
using diverse datasets.
Speech Dataset
This study used three publicly accessible datasets for
the speech-based emotion recognition (SER) model: Ban-
glaSER, Toronto Emotional Speech Set (TESS) and Ryer-
son Audio-Visual Database of Emotional Speech and Song
(RAVDESS)[31][32][33]. The BanglaSER dataset contains
recordings of people speaking Bengali while displaying vari-
ous emotions. It helps researchers work on emotion recog-
nition technology for Bengali, which lacks sufficient data re-
sources. The TESS dataset consists of audio clips from two
female actors who performed seven different emotions using
a fixed list of target words.RAVDESS is a popular dataset
that researchers use as a standard for testing emotion recog-
nition. It has recordings of 24 professional actors speaking
and singing with different emotions.

Image Dataset
For facial expression recognition (FER), the FER-2013
dataset was chosen[34]. It contains 35,887 grayscale im-
ages that are categorized into seven emotion groups: anger,
disgust, fear, happiness, sadness, surprise, and neutral. In-
troduced during the ICML 2013 Challenges in Representa-
tion Learning workshop, it remains a popular dataset for con-
volutional neural network (CNN) based emotion classifica-
tion.
Text Dataset
The text-based emotion detection model employed two
English and one Bengali text dataset to cover linguistic diver-
sity and provide contextual emotional representations. These
datasets from Pashupati Gupta[35], Thufiq Ahmed Nahian[36],
and Sima Anjali[37]. All provide manually annotated text
samples reflecting emotions like happiness, sadness, anger,
fear, and surprise.
Multi-modal Fusion dataset
The fusion model in this study was developed and eval-
uated using the MELD (Multimodal EmotionLines Dataset)
[38], a widely used benchmark for multimodal emotion recog-
nition. MELD provides synchronized audio, text, and visual
data extracted from real conversational interactions, making
it well suited for training early-fusion architectures that rely
on cross-modal alignment. Each dialogue segment in MELD
includes a facial image frame, the corresponding spoken au-
dio clip, and its textual transcription, along with emotion la-
bels across multiple classes such as neutral, happy, anger,
sadness, fear, disgust, and surprise. This multimodal struc-
ture allowed the proposed model to learn complementary
emotional cues across modalities, while the dataset’s con-
versational nature introduced realistic variability in tone, ex-
pression, and context. Using MELD ensured that the fusion
system was trained on heterogeneous, real-world emotional
expressions, enabling more robust and context-aware emo-
tion recognition.

# Music-Genre-Classification using Spectograms(2D CNN)
This is a music genre classification project made for 'Neural Networks and Deep Learning' course during the master degree. The fma_small data was used from https://github.com/mdeff/fma.

The purpose of this project is classifying music genres
based on their spectrogram using CNN model. The goal of
this is getting higher accuracy compared to other classification
models. In the project, the CNN is used as a classification
model since the image representation of the audio files are
used. The project is consists of multiple data pre-processing
steps to get the image representation of the audio files and
labeled the data

In the first step of the project 800 .wav files were recorded
and 800 spectrogram images were saved to the folders for each
genres. However , because the limitation of the RAM capacity
and the GPU issues the model could not be trained using all
the data for each genres. Thus, 600 images were considered for
each genre and the they were tried to classified by separating
different groups. For example [pop,instrumental, electronic]
and [hiphop, rock, folk]. When we tried to get more than 3
genres the colab environment tends to collapse. Also, we tried
to use more than 3 genres or all the genres with less amount
of images (such as 200 or 300 for each), however the accuracy
could not obtained properly with less amount of data. Thus,
600 images were used for each genre by grouping them.

![spec_1](https://user-images.githubusercontent.com/14100704/226654676-129e2b95-0756-4b9b-b504-25cef28aca8a.PNG)

![acc_1](https://user-images.githubusercontent.com/14100704/226655141-ae19234f-dc48-4985-9d4e-479fbc04b795.PNG)

![acc_2](https://user-images.githubusercontent.com/14100704/226655173-53692fcb-798a-4d93-9422-07e85b517c91.PNG)

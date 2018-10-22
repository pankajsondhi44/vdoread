# vdoread
An application which enables blind people to visualize any video using image captioning and text to speech conversion

# how to run
All this will be better if you store everything in the directory where your prebuilt python libraries are stored.

1. Download the Pre Trained Model of Multiple Object Detection and captioning:- 
  a)Run the download_model python file to download the pretrained model on the MSCOCO dataset.
  b)Make the following changes in the download_model file before running. Change the path in the variable name patmodel to your pc             location (Create an etc folder in the python36 directory). After running that file the model will appear as show-and-tell-2M.zip and       simultanously as .pb file.
2. Copy the show_and_tell_model.py, vocab.py and caption_generator.py in lib folder.
3. Copy the word_counts.txt file to the etc folder.
4. Copy the inference.py to the python36 library.
5. Now selct an image for generating captions and copy it to the etc folder.
6. Set the Flag variables to the respective paths in the inference file.
7. Run the inference file directly.
8. Top 3 Captions will be generated.

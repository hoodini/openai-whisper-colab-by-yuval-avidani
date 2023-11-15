# **OpenAI's Whisper transcriber by Yuval Avidani - יובל אבידני**

**Please support with Beer: https://linktree.com/hackit.co.il**

**IMPORTANT: V100/A100 GPU IS REQUIRED TO USE THIS NOTEBOOK! OTHERWISE THE NOTEBOOK WILL CRASH AND WILL SHOW CUDA MEMORY ERROR MESSAGES**

This notebook has the followings capabilities:

1. Select between YouTube URL and Media Files Upload
2. YouTube Videos are downloaded and convereted to WAV
3. Uploaded media files are also being converted to WAV
4. File size check is made to adhere to Whisper's file limit size of 25MB
5. If the file is larger, the notebook uses Smart Chuncking
6. It then transcibes each chunk and concataned it all to one SRT / TXT file
7. The files can be downloaded using the last cell

**Instructions:**
1. Run cells 1-2
2. Run cell 3 and note to choose your media source (YouTube URL / Upload Media File)
3. Run cell 4 to get transcription in SRT / TXT format
4. Run cell 5 to download SRT / TXT
Note: the files can also be downloaded from the file explorer on the sidebar.

Enjoy!

**Don't forget to stand with the truth! Stand with Israel against Hamas!**

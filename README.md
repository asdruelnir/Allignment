# Cognitive Annotation 2022

For group 5 2022:
1. Get the name of the dyad assigned to you under **cognition.csv**, and download that wav file from https://drive.google.com/drive/folders/1uyIt28QFXhtY8NaBLhzX3MFucb0fCboe?usp=sharing
2. Optionally, download the mp4 file to see the video version for easier annotation (do not open video in Praat)  
3. Open the wav file using Praat (https://www.fon.hum.uva.nl/praat/).
4. Select the file in the taskpane and click Annotate- To TextGrid...
5. Remove Mary John and both bell from textboxes
6. Add ChineseSpeaker ColombianSpeaker for All tier names:
7. Click Apply
8. Select Both Sound and TextGrid using Shift and Click then click View & Edit
9. You will now begin segmenting the ChineseSpeaker and ColombianSpeaker tiers based on the rules listed at https://www.beautiful.ai/player/-Mv63a4WQKlK8WC6tgHX/Reglas
10. If you don't know how to use Praat to segment the tiers, watch the Praat tutorial *https://github.com/Allignment/Allignment/blob/main/TUTORIAL-UAN.mp4* from the Alignment Repository Project. This is a different project, but you can see how to navigate Praat.

# Allignment Repository

There are several interactions in this repository, each one with two files associated, first, a transcription file in **textgrid** format (which may have some errors) and second an audio file in .wav format corresponding to that transcription. You'll find both files for each interaction in the following Google Drive folder. 

Google drive link: https://drive.google.com/drive/folders/1EKgWmTmJ9399LF_ljGKqdG7zCRPvzmxs?usp=sharing

In the *assignments.csv* file you'll find what are the interactions assigned to you.

Given an interaction assigned to you, you must download the respective audio files to your local computer, pull the git projects, and also download Praat editor for opening these files. You can download it clicking in the following link:

Praat link: https://www.fon.hum.uva.nl/praat/

You'll find a tutorial for using Praat by professor David Herrera in the *TUTORIAL-UAN.mp4* file.

This tutorial is simple since using Praat is really easy and intuitive. All you have to do is open both files in the Praat editor following the instructions in the tutorial, and the rules in https://github.com/Allignment/Allignment/blob/main/transcription_rules.pdf and then edit the transcription file completing the following tasks:

- **Correct Misspelling errors:** Despite that the transcription is already done, there may be some errors that you should recognize and correct so that the transcription is clean. For instance, in some files there are some *annotations* written in spanish, you should replace them appropiately.
- **Transcribe and normalize backchannels and fillers**: You should recognize when people uses backchannels or fillers and then transcribe them if they're not. If they are allready transcribed you must replace them with the apporpiate ones, as the *transcription_rules.pdf* indicates.
- **Align transcription and audio**: Despite that most of the interaction is already alligned, you should polish details.

When you have finished your work, you should update the appropiate textgrid file in the *files* folder of this repository, by sending a pull request.

If you haven't used Git before and don't know how to clone this repository to your local machine or send pull requets, please check the following tutorial:

https://www.youtube.com/watch?v=ukJEPyKubzA

If you have any doubt, don't hesitate to contact jupgomezme@unal.edu.co or dherreraal@unal.edu.co.

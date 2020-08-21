# covid_data_telephone_band

Data used for "COVID-19 PATIENT DETECTION FROM TELEPHONE QUALITY SPEECH DATA"

Telephone band speech data with 8kHz sampling rate. (300 Hz - 3.4kHz)

Download the data, then you can merge the split tar files using the command below to obtain a single tar file and then untar it.

cat *.tar.gz.* > file_name.tar.gz

tar -xvzf file_name.tar.gz


This folder has 19 speakers data ( 7 females + 12 males ), out of which 10 (4F + 6M ) are positive and 9 ( 3F + 6M) ar negative. 
Each folder is named after the speaker 
       Eg: F01, F02 etc., (indicates Female speaker with speaker ID 01, 02 etc.)
similarly, M04, M05 etc.. (indicates Male speaker with speakerID 04, 05 etc.)

In each folder there are telephone band speech data (with 8kHz sampling rate) named as follows 
Eg: F01sent_01.wav --
          F - Gender (female/male)
         01 - Speaker ID
    sent_01 - utterance ID
    .wav    - wave file extension

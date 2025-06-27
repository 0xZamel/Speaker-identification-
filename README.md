Speaker Identification using MFCC and DTW (C#)

-----------------------------------------------------
Overview:
-----------------------------------------------------
This project is a speaker identification system built in C#. 
It uses MFCC (Mel-Frequency Cepstral Coefficients) to extract 
features from audio and compares them using DTW (Dynamic Time Warping).

A pruned version of DTW is also implemented for faster performance.

-----------------------------------------------------
Features:
-----------------------------------------------------
- Extracts MFCC features from WAV audio files
- Compares test samples with known speakers using DTW
- Supports both normal DTW and pruned DTW
- Identifies the most likely speaker from a test sample

-----------------------------------------------------
Technologies Used:
-----------------------------------------------------
- C# (.NET)
- NAudio (for audio processing)
- Custom MFCC and DTW implementations

-----------------------------------------------------
Folder Structure:
-----------------------------------------------------
- /AudioSamples        → Speaker WAV files
- /Features            → Extracted MFCC features
- /DTW                 → DTW and Pruned DTW logic
- /Models              → Stored speaker templates
- /Results             → Output from test runs
- Program.cs           → Main program entry

-----------------------------------------------------
How to Run:
-----------------------------------------------------
1. Make sure you have all WAV files in /AudioSamples
2. Open the project in Visual Studio or run it using dotnet CLI
3. Build and run the solution
4. The program will extract MFCCs and identify the speaker

You can select between DTW and Pruned DTW in the code config.

-----------------------------------------------------
Example Output:
-----------------------------------------------------
> Speaker Identified: Speaker_03
> DTW Distance: 124.53
> Method Used: Pruned DTW

-----------------------------------------------------
Author:
-----------------------------------------------------
- Omar Zamel  
- Ibrahim Yasser  
- Ibrahim Saad  
- Adham Hussam

Ain Shams University – Computer Science

-----------------------------------------------------
License:
-----------------------------------------------------
For academic and educational use only.
Commercial use requires permission.

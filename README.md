# seriousPrank
## Basic Details
### Team Name: ERROR404
### Team Members 
- Member 1: Ruban T Jose - Viswajyothi College of Engineering and Technology
- Member 2: Nivin K Sunil - Viswajyothi College of Engineering and Technology
### Project Description
It is a mischievous Python prank that floods the screen with dozens of tiny looping video windows, turning any calm desktop into a chaotic movie marathon. Packed with VLC so it runs anywhere, it’s portable, sneaky, and guaranteed to confuse your friends. Use it for laughs—just be ready for revenge!

### The Problem (that doesn't exist)
People’s desktops are far too calm and organized, lacking the excitement of dozens of tiny videos dancing across the screen. Clearly, the world suffers from a shortage of chaotic visual mayhem to keep computer users on their toes.

### The Solution (that nobody asked for)
 It Python-powered chaos engine that floods the screen with looping video windows, creating instant confusion and maximum entertainment. It’s the perfect answer to a problem no sane person ever had.

## Technical Details
### Technologies/Components Used

**Languages used**  
- Python  

**Frameworks used**  
- None (standalone Python script)  

**Libraries used**  
- `python-vlc` – for video playback  
- `pywin32` (`win32gui`, `win32con`) – for window positioning and control  
- `time` – for timing and delays  
- `os` – for file path handling (if portable setup used)  

**Tools used**  
- VLC Media Player (runtime for playback)  

### Implementation
Implemented entirely in Python

## Installation
Install the required Python libraries: pip install python-vlc pywin32

## Run
To run the Python script directly: python "virus prank.py"

### Project Documentation
This prank software is designed to overwhelm a desktop with multiple looping VLC video windows positioned in different areas of the screen. It leverages the python-vlc library to handle media playback and pywin32 for window positioning and resizing. The software is packaged into a .exe using PyInstaller for portability, and optionally distributed via an Inno Setup installer that includes all dependencies (VLC runtime, videos, and executable) for plug-and-play use on any Windows PC.

The implementation focuses on:

- Automated Video Looping – Videos restart immediately upon completion.
- Dynamic Window Management – Windows are resized and moved programmatically.



## Screenshots (Add at least 3)
https://drive.google.com/drive/folders/1MkE6LhlXgb-bBPmvnWXimcUQSFmzbK2b

## Diagrams
workflow diagram link: https://drive.google.com/drive/folders/1BsI4RghcmmoGJoaQVnUFlQEAvSAI_wrv
- The prank begins when the program is launched, loading the bundled video files into multiple VLC media player instances. These windows are automatically spawned across the screen, resized, and positioned for maximum chaos. Each video loops endlessly until the user manually closes all windows or terminates the program, often leading to confusion and laughter.


### Project video Demo
[## Video
[Add your demo video link here] Explain what the video demonstrates](http://drive.google.com/drive/folders/1XsC6LlVib2FpdubWp06mXGPFye3Y8Qdj)


### Team Contributions
- **Ruban T Jose** – Idea, debugging, packaging, testing, documentation  
- **Nivin K Sunil** – Python development, packaging, testing  

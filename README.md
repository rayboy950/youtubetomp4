Youtubetomp4 Web App
Youtubetomp4 Web is a lightweight, simple-to-use application that allows users to download YouTube videos in MP3 or MP4 formats. You can choose the quality for both formats, and the app runs locally on your machine with no need for an internet connection after the initial setup.

Features:
Download YouTube content as MP3 or MP4.
Select from different video quality options for MP4 downloads.
Easy-to-use UI with no need for technical setup.
Runs locally, keeping your privacy intact.
Lightweight application (less than 20 MB).
Supported Formats:
MP3 (audio only, with adjustable bitrate).
MP4 (video and audio combined, with adjustable quality).
Installation Guide
Prerequisites:
Python 3.7+ (If you want to run the source code yourself, otherwise, use the packaged executable below)
ffmpeg (Required for video/audio processing, included in the packaged app)
Using the Executable (For Non-Developers):
Download the executable:

Go to the Releases section of the GitHub repository.
Download the .exe file (Windows) or corresponding executable for your operating system.
Run the executable:

Double-click on the downloaded .exe (or app for macOS) to launch the application.
The app will open in your default web browser at http://127.0.0.1:5000/.
Use the app:

Enter the URL of the YouTube video you want to download.
Choose between MP3 or MP4 formats, and select your desired quality (for MP4).
Click download, and the app will save the file to your computer.
Running from Source Code (For Developers):
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/Youtubetomp4-Web.git
cd Youtubetomp4-Web
Set up a virtual environment:

bash
Copy code
python -m venv venv
Activate the virtual environment:

Windows:
bash
Copy code
venv\Scripts\activate
macOS/Linux:
bash
Copy code
source venv/bin/activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the app:

bash
Copy code
python app.py
The app will be available in your browser at http://127.0.0.1:5000/.

Minimum System Requirements
To run the app smoothly, your system should meet these minimum specifications:

Operating System: Windows 7+, macOS 10.10+, or any Linux-based OS.
Processor: Dual-core CPU (2.0 GHz or faster).
RAM: 4 GB or more.
Storage: 100 MB free space for the app and its dependencies.
Internet Connection: Required only for downloading YouTube content.
For better performance, an SSD and a multi-core processor will speed up the download and conversion processes, especially for video files.

How to Use the App
Start the app: Open the app by running it locally (or double-click the executable if you’re using the packaged version).
Enter the YouTube URL: Paste the URL of the YouTube video you wish to download in the input field.
Choose format and quality:
Select MP3 for audio-only downloads (with adjustable bitrate).
Select MP4 for video downloads (choose the desired video quality).
Download: Click the Download button to start the process. Once the download is complete, you’ll be able to access the file in the folder you specified.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Notes
The app uses yt-dlp for downloading YouTube videos and ffmpeg for media conversion. Both of these tools are bundled within the app.
The app runs locally on your machine, so your privacy is maintained, and no external servers are used to process your downloads.

# birdbrush
BirdBrush is a digital painting software designed with help from Google's Gemini tool.

It is part of the BirdOffice suite of minimalist but usable software for Windows and macOS.

BirdBrush was founded in August 2024 whenever I was looking for a tutorial to make a painting app in Python. Most of the resources I found had restrictive copyright licenses, which hindered my creative efforts.
To escape copyright, I turned to Google Gemini. 

With some guidance, the two of us managed to produce BirdBrush, which I now license under the Unlicense, such that other people can freely use and modify my software without the limits imposed by copyright law.

# Regarding exporting files
BirdBrush saves files under the BBF 1 format, which was designed specifically for use with BirdBrush.

If you need another format, just take a screenshot of your painting.

Developers: If you can manage to implement PNG/JPG exporting support, please open a pull request. Your efforts will be much appreciated.

# Usage
It's quite simple: select a color, draw something, and save it.
If you need more help, open an issue or email mojavesoft@gmail.com.

# Building from source
To build BirdBrush from source, first install the latest version of Python 3. BirdBrush is built on Python 3.12, so we recommend using 3.12 for the best experience.

Then, download a buildkit from the Releases tab. The buildkit will work on either Windows or macOS as long as Python is in your PATH (`python` for Windows, `python3` for macOS).

To build from source, extract the buildkit and run your operating system's respective build script (`build_paint.bat` for Windows, `sudo bash ./build_paint.sh` for macOS).

The build script will install/update all required modules (`pyinstaller`, `tk-tools`, and `pillow`) and produce an executable file in the `dist` folder.

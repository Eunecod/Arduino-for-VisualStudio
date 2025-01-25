# Arduino Project Using WinAVR

This project is designed for developing software for AVR microcontrollers using WinAVR in the Visual Studio environment.

## Installing WinAVR

1. **Download WinAVR**:
   - Go to [this link](http://sourceforge.net/projects/winavr/) to download the latest version of WinAVR.

2. **Install WinAVR**:
   - Run the downloaded installer and follow the on-screen instructions.
   - It is recommended to install WinAVR in a directory without spaces or Cyrillic characters, such as `C:\WinAVR`.

## Setting Up the Path

After installing WinAVR, you may need to add the path to its executables in the Windows environment variables:

1. Open the "Control Panel" and go to "System".
2. Click on "Advanced system settings".
3. In the "Environment Variables" section, find the `Path` variable and select "Edit".
4. Add the path to the `bin` folder inside your installed WinAVR directory (e.g., `C:\WinAVR\bin`).

## Moving the Include Folder

If you want to use your own header files or libraries, move the `include` folder to a location that suits you and update your project paths to point to the new location.

## Saving Files Without UTF-8 BOM

For proper compilation of files using the AVR compiler, it is necessary to save them without BOM (Byte Order Mark). Here’s how to do it:

1. If you are using a text editor like Notepad++, follow these steps:
   - Open the file.
   - Go to the **Encoding** menu.
   - Select **UTF-8 without BOM**.
   - Save the file.

2. If you are using another editor, make sure it supports saving files without BOM.

## Conclusion

By following these instructions, you will be able to set up your development environment for working with Arduino and AVR microcontrollers using WinAVR. If you have any questions or issues, feel free to reach out for help.

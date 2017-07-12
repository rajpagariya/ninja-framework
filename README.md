# Ninja Framework
This framework serves two purposes: Directory Enumeration & Service Fingerprinting.
### Directory Enumeration
This framework uses dirb for directory enumeration. It asks a user whether he wants to do a default(basic) scan or do an advanced scan. In Advanced scanning mode, it provides a list of wordlist files available with it.
### Service Fingerprinting
This is a framework for scanning network ports, their services and saving the results as screenshots to make your job easier. It uses nmap and scrot. You can use this framework in either network mode or single-host(device) mode.
###### In network mode: 
1. It scans the given range of IP addresses one-by-one using default group of scrips.
2. It uses default group of scripts to reduce the time complexity.
3. It generates the report by saving the screenshot of the output by creating a folder for each IP Address. For example, if the IP Address of the network device is 192.168.0.2, then it will save the screenshot in a folder named 192.168.0.2. This folder will be created inside the Ninja folder on your Desktop.
###### In single-device mode:
1. It will ask you to choose between default scripts, particular group of scripts or the best-of-all scripts.
2. In the particular group of scripts, it will ask you whether you want to scan the target with each and every group of script.

## Getting Started
1. Compatibility: Any Linux flavor having nmap, dirb and scrot installed. 
2. If you are working on Kali Linux, then nmap and dirb are already installed on your computer.
3. Check whether nmap is installed on your computer. If not, install it from [here](https://nmap.org).
4. Check whether dirb is installed on your computer. If not, run the following command: `sudo apt-get install dirb`.
5. Install scrot on your computer by running the following command on the Terminal: `sudo apt-get install scrot`.
6. Use Terminal in full-screen mode for better results for Directory Enumeration as well as Service Fingerprinting.
7. Also, for better and accurate results, Zoom Out twice in the terminal. The option to Zoom Out in terminal is given under `View` dropdown. Alternatively, you can press `Ctrl + - ` twice to do the same.

## Running the Script
1. Download or clone this repository. Unzip.
2. There are three files in the folder extracted: `ninja`,`fingerprinting`, and `directorybuster`. Copy all these files in your `root` directory.
3. Make sure that this file is executable by running the following command: `chmod +x ninja`,
4. Simply run the file by typing `./ninja`.
5. It will ask you what do you want to do: Directory Enumeration or Service Fingerprinting. Enter your choice accordingly.
6. Please note that this framework does not take screenshots in Directory Enumeration Mode.
7. In Service Fingerprinting mode, a beep tone at the end will notify that the screenshot of the output screen has been taken and a particular execution process has been completed.

## Author Contact Details
Raj Pagariya (@rajpagariya)
- [Facebook](https://www.facebook.com/rajp05) | [Twitter](https://www.twitter.com/rajpagariya) | [LinkedIn](https://www.linkedin.com/in/rajpagariya/)
- rajpagariya[at]hotmail(dot)com

## Credits
This project has been developed under the mentorship of Mr. Yogesh Ranjan Upadhyay (Director, [Ninja Info-Sec Services Pvt. Ltd.](www.ninjasecurity.co.in)) during my summer internship. He can be reached at director[at]ninjasecurity[dot]co[dot]in.

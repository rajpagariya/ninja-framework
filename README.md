# Ninja Framework
This is a framework for scanning network ports, their services and saves the results as screenshots to make your job easier. It uses nmap and scrot. You can use this framework in either network mode or single-host(device) mode.
###### In network mode: 
1. It scans the given range of IP addresses one-by-one using default group of scrips.
2. It uses default group of scripts to reduce the time complexity.
3. It generates the report by saving the screenshot of the output by creating a folder for each IP Address. For example, if the IP Address of the network device is 192.168.0.2, then it will save the screenshot in a folder named 192.168.0.2. This folder will be created inside the Ninja folder on your Desktop.
###### In single-device mode:
1. It will ask you to choose between default scripts, particular group of scripts or the best-of-all scripts.
2. In the particular group of scripts, it will ask you whether you want to scan the target with each and every group of script.

## Getting Started
1. Compatibility: Any Linux flavor having nmap and scrot installed. 
2. Check whether nmap is installed on your computer. If not, install it from [here](https://nmap.org).
3. Install scrot on your computer by running the following command on the Terminal: `sudo apt-get install scrot`.
4. Use Terminal in full-screen mode. Also, for better and accurate results, Zoom Out twice in the terminal. The option to Zoom Out in terminal is given under `View` dropdown. Alternatively, you can press `Ctrl + - ` twice to do the same.

## Running the Script
1. Download or clone this repository. Unzip.
2. Change your present directory on Terminal to the location where you have extracted the downloaded zip file.
3. Make sure that the file is executable by running the following command: `chmod +x ninja`
3. Simply run the file by typing `./ninja`.
4. It will ask you whether you want to use it in network mode or singe-host mode. Choose your mode and follow instructions given along with each step.
5. Just in case you go for specific script groups, it will clear the screen before proceeding to the next step.
6. A beep tone at the end will specify that the screenshot of the output screen has been taken and a particular execution process has been completed.

## Author Contact Details
Raj Pagariya (@rajpagariya)
- [Facebook](https://www.facebook.com/rajp05) | [Twitter](https://www.twitter.com/rajpagariya) | [LinkedIn](https://www.linkedin.com/in/rajpagariya/)
- rajpagariya[at]hotmail(dot)com

## Credits
This project has been developed under the mentorship of Mr. Yogesh Ranjan Upadhyay (Director, [Ninja Info-Sec Services Pvt. Ltd.](www.ninjasecurity.co.in)) during my summer internship. He can be reached at director[at]ninjasecurity[dot]co[dot]in.

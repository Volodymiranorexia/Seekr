# Seekr
Find IP and location on target
Thanks to TheWhiteh4t for this software.

Find location and IP of any target.

1 apt update
2 apt install git
3 clone into seeker by command " git clone" followed by copied link
4 type "ls" to see if seeker is present
5 Head over to ngrok website and create profile, signup page
6 Head over to tempmail.org to create a temporary mail address (this will be used for ngrok signup)
7 Now enter the temp mail generated inside ngrok signup, and go back to temp mail to verify the email address.
8 Download ngrok, youll have a .tgz file in downloads
9 Open a new terminal type " cd Downloads" to get into downloads folder
10 Type "ls" to list downloads. ngrok should be there now hence you just downloaded it. Copy this link to folder path
11 Paste the folder path in your terminal "tar -xf ngrok-v3-stable-linux-amd64.tgz"
12 type "ls" to see that it has been listed
13 Type "chmod +x ngrok" Note the "x" is not multiply sign, its an ex"
14 Go back to your ngrok acc and copy your "AuthToken" and paste it in the terminal eg ./ngrok config add-authtoken 2Tghbn677474556.....
15 You will see the authtoken has been saved to config file
16Now type "ngrok http 8080" and press enter. You should now be in.

17 Go back to root terminal and type "ls" to see if seeker is present.
18 Type "cd seeker" 
19  Type "ls" again
20 Type "chmod +x install.sh
21 Type "./install.sh" Python 3, PIP and PHP should now install
22 Now type " python seeker.py' and seeker should open.
23 From the list you can choose which option you want to use by typing a nr 1,2,3,4,5,6,7 or 0
After choosing an indication will be given that template was loaded 


Head back to the non root terminal and type "./ngrok http 8080" and copy the Forwarding link. dont copy the part from the arrow onwards, everything before the arrow can be copied. This link is the link sent to the target.

When the target clicks on the link, you will see the info on their location, IP, browser they use, Operating system, GPU, Country and so on.



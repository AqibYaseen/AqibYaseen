- 👋 Hi, I’m @AqibYaseen
- 👀 I’m a Frontend Developer ...
- 🌱 I’m currently learning Angular["80%"], Docker & C# ...
- 💞️ I’m looking to collaborate on any Frontend Project ...
- 📫 How to reach me mail-to : aqibyaseenbhat@gmail.com


Step 1: Download latest or recommended node .tar.xz file from https://nodejs.org/en/

or you can download node version 14.15.5 (.tar.xz file) directly from here ->

https://nodejs.org/dist/v14.15.5/node-v14.15.5-linux-x64.tar.xz

Step 2: Go to the directory in which (.tar.xz file) is downloaded.

In my case --> /Download directory

Step 3: Update System Repositories

sudo apt update

Step 4: Install the package xz-utils

sudo apt install xz-utils

Step 5: To Extract the .tar.xz file

sudo tar -xvf name_of_file

In my case --> sudo tar -xvf node-v14.15.5-linux-x64.tar.xz

Step 6: sudo cp -r directory_name/{bin,include,lib,share} /usr/

In my case --> sudo cp -r node-v14.15.5-linux-x64/{bin,include,lib,share} /usr/

Step 7: Update the Path export PATH=/usr/node_directory_name/bin:$PATH
In my case --> export PATH=/usr/node-v14.15.5-linux-x64/bin:$PATH

Step 8: Check the node version

node --version

Result In my case -> v14.15.5


<!---
AqibYaseen/AqibYaseen is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

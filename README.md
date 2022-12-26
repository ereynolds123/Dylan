# Dylan

Step 1: Set up a Git Account. https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account

Step 2: If you are feeling fancy, set up SSH. https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

Step 3: On the command line, clone down the Dylan repo. 

Step 4: Install Homebrew
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
The script will explain what changes it will make and prompt you before the installation begins. Once you’ve installed Homebrew, insert the Homebrew directory at the top of your PATH environment variable. You can do this by adding the following line at the bottom of your ~/.profile file

export PATH="/usr/local/opt/python/libexec/bin:$PATH"

Step 5: Install python 
In command line, type brew install python

Step 6: In the folder with the repo, run the command python script.py


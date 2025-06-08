# remote-server-setup
Solution to an exercise to connect to a DigitalOcean droplet on Linux OS.
1. Open a session on the terminal
2. Generate a ssh keypair:
    - use the command:
     ```
     ssh-keygen
     ```
3. Check if the key pair has been generated with:
   ```
   cat ~/.ssh/[file name].pub
   ```
4. Go to the DigitalOcean website and stand up a Droplet
5. Connect to the droplet with the command:
   ```
   ssh -i [/path/to/public key] [user]@[droplet IP]
   ```
6. SSH will connect to the droplet

The original exercise can be found at: https://roadmap.sh/projects/ssh-remote-server-setup

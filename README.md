# jMusicBot_TrueNAS_Scale
Running jMusicBot on TrueNAS Scale Docker

Work based on repackaged jagrosh MusicBot https://github.com/jagrosh/MusicBot/ by https://github.com/yojoshb/jmusicbot-docker

Requirement : Discord Bot must be created

# Step 1 - Setting up the Docker folder on TrueNAS Scale

Create a folder on your TrueNAS Scale to host jMusicBot configs

```
mkdir -p /mnt/Your_Pool/Docker/jMusicBot
```

# Step 2 - Copy all the files to this folder

config.txt

# Step 3 - Edit config.txt with your credentials

Here are the mandatory fields to update
token // See https://github.com/jagrosh/MusicBot/wiki/Getting-a-Bot-Token
owner // See https://github.com/jagrosh/MusicBot/wiki/Finding-Your-User-ID

# Step 4 - Setup a docker instance on TrueNAS Scale

Application Name = Your choice
Image repository = ghcr.io/yojoshb/jmusicbot-docker
Image Tag = Latest
![image](https://github.com/T13nou/jMusicBot_TrueNAS_Scale/assets/64090484/0f68021d-d48f-4a7a-82e2-8f7e0442101d)

Set the directory you created as additional storage
![image](https://github.com/T13nou/jMusicBot_TrueNAS_Scale/assets/64090484/9240c73b-0712-4c1b-b91d-2ec52e74476d)

# Step 5 - You're done

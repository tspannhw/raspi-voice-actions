# raspi-voice-actions
Created this repo to separate custom code from the default aiyprojects-raspbian repo code.  

## Custom actions for AIY Projects
Custom actions for https://github.com/google/aiyprojects-raspbian/blob/master/src/action.py

## Symlink
After cloning the repo, setup a symlink to ~/voice-recognizer-raspi/src/action.py
```bash
# Backup current action.py
cp ~/voice-recognizer-raspi/src/action.py ~/voice-recognizer-raspi/src/action-backup.py

# Remove current action.py
rm ~/voice-recognizer-raspi/src/action.py

# Create the symlink
sudo ln -s ~/raspi-voice-actions/action.py action.py
```

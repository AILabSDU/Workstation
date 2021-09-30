## Security 
SDU does not allow VPN access to students and professors. Therefore, we will connect to the computer with a GPU as a remote computer. 
Therefore, only a single user can connect to the computer at a time. Also, all users can access to all aplications installed in the computer. 

**Please log out from all applications that you used during your session, so other users will not have access to your credentials!**

## Access
1. Please install [AnyDesk](https://anydesk.com/en) according to your platform. 
2. After launching AnyDek please enter the following Remote Desk ID: **673490380**
3. You will be provided with a password to login. Don't share the password with anyone. Please enter that password next. 
4. You should see the desktop of the remote computer running on Linux next. 


## Run python scripts 
1. Prepare your file_name.py file 
2. Open the terminal by pressing ```Ctrl+Alt+T```
3. Type ```python file_name.py```

Sometimes it is convinient to let a code to run in background.
In such cases, you can use ```tmux```, a terminal multiplexer. 
1. Open the terminal by pressing ```Ctrl+Alt+T```
2. Type ```tmux new -s mysession```, where ```mysession``` referres to the name of your session
3. Run python script using ```python file_name.py```
4. Detach from a tmux session, which will keep running by typing ```Ctrl+b``` and then ```d```
5. To attach back to the session go to terminal and type ```tmux attach mysession```
6. To kill a session on tmux type ```Ctrl+x``` and press ```y```
Please refer here to get a full list of [tmux commands](https://tmuxcheatsheet.com/)


## Learn GPU usage 
1. To check whether your code runs on a GPU please go to terminal. 
2. Type nvidia-smi
3. You should see the following image 



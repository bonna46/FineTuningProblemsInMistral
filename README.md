# FineTuningProblemsInMistral
## Make virtual environment and install them
sudo pip3 install pytorch
sudo pip3 install ipywidget

## Connecting with Jupyter through server
1.ssh into the server [ command -> " ssh username@ip-address "]
2.do command - " jupyter notebook --no-browser --port=8888 "
3.copy the token
4.open another terminal
5.do command = " ssh -L 8888:127.0.0.1:8888 <user>@<IP> "
6.open browser
7.do localhost:8888
8.enter the token
9.use Jupyter

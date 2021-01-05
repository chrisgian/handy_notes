https://github.com/chrisgian/handy_notes.git

```
python -m ipykernel install --user --name [NAME] --display-name "Python ([NAME])"
```


Be able to connect to remote jupyter
```
# https://benjlindsay.com/posts/running-jupyter-lab-remotely

# in terminal one after ssh ...
jupyter lab --no-browser --port=5678
# connect in 2nd terminal window
ssh -CNL localhost:5678:localhost:5678 username@hostname
```

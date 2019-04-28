# Tunneling guide for myself

I'm gonna update this as I learn more about tunneling.

## Jupyter Notebook

1. ssh to smt

    ssh -L localhost:8989:localhost:8989 vinicius.pinho@loghost.smt.ufrj.br

2. ssh to a remote machine

    ssh -L localhost:8989:localhost:8989 vinicius.pinho@moscou.smt.ufrj.br

3. open jupter notebook

    jupyter notebook --no-browser --port=8993 &

4. copy the link and have fun

## VSCode

1. ssh to smt
 

    ssh -R 52698:localhost:52698 vinicius.pinho@loghost.smt.ufrj.br

 2. ssh to a remote machine
 

    ssh -R 52698:localhost:52698 vinicius.pinho@moscou.smt.ufrj.br

 3. open a remote file 

     rmate -p 52698 softmax.py 

That's it for now.



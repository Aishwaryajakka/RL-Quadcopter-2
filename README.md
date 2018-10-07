# DeepRL Quadcopter Controller

_ Guide the four-axis aircraft to learn to fly! _

In this project, you will design a deep reinforcement learning agent to control the flight of several quadcopters, including take-off, hover and landing.

## project instruction

1. Copy the code base and browse the download folder.

```
Git clone https://github.com/udacity/RL-Quadcopter-2.git
Cd RL-Quadcopter-2
```

2. Create and activate a new environment.

```
Conda create -n quadcop python=3.6 matplotlib numpy pandas
Source activate quadcop
```

3. Create an [IPython kernel] for the `quadcop` environment (http://ipython.readthedocs.io/en/stable/install/kernel_install.html).
```
Python -m ipykernel install --user --name quadcop --display-name "quadcop"
```

4. Open notebook.
```
Jupyter notebook Quadcopter_Project.ipynb
```

5. Before running the code, use the drop-down menu (**Kernel > Change kernel > quadcop**) to modify the kernel to accommodate the `quadcop` environment. Then follow the instructions in the notebook.

6. In order to complete this project, you may also need to install additional pip packages. Check out the `requirements.txt` file in the codebase for the packages you need to run your project.

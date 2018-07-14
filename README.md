# Tutorials

## Table of Contents

* [What is it?](#what-is-it)
* [Directory Structure](#directory-structure)
* [Usage](#usage)
    - [Local Usage](#local-usage)
    - [Web Usage](#web-usage)
* [Contributors](#contributors)
* [License](#license)

## What is it?

A set of simple tutorials that explain MCMC (**M**arkov **C**hain **M**onte **C**arlo).

A short description of the motivation behind the creation and maintenance of the project. This should explain **why** the project exists.

## Directory Structure

TODO

<!---```
 master/
 ├── tutorials/
 |   ├── part1/
 |   |   ├── figs/                             # Figures folder
 |   |   └── linear_model_mcmc.ipynb           # Part1 of tutorial
 |   ├── part2/
 |   |   └── Currently doesn't exist... waiting on Nihar 
 |   ├── part3/
 |   |   ├── gev_distribution_fitting.ipynb    # Part3A of tutorial
 |   |   └── normal_distribution_fitting.ipynb # Part3B of tutorial
 |   └── part4/ 
 |       └── Currently doesn't exist
 ├── .gitignore
 └── README.md
```-->

## Usage

### Local Usage

**Installing Jupyter:** Before you play around with our tutorial, first install Jupyter Notebook:

```sh
pip install jupyter
```

Please note that if `pip` is connected to Python 2.7 on your computer, then you can also try `pip3`. You can also install [Anaconda Python 3.6](https://www.anaconda.com/download), which downloads both Python 3.6 and Jupyter.

**Cloning Repo & Starting Jupyter Server:** After you have installed Jupyter, run the following commands:

```sh
# Clone the tutorial repo
git clone https://github.com/MUSSLES/tutorials.git
# Go to the repo directory
cd MCMC_Tutorial
# Start the Jupyter server
jupyter notebook
```

After executing the last command, you should be redirected to a localhost server in your browser. Click on the tutorials you want to view, which are listed above... and have a blast!

### Web Usage

**TODO**

## Contributors

Please enjoy the code and offer us any suggestions. It is our aim to make the tutorials accessible and usable by all, so that anyone can easily pick up MCMC thinking. We are always interested to hear about potential improvements to the tutorial... [suggestions](../../issues/) and pull requests are highly encouraged!

Questions? Tony Wong (anthony.e.wong@colorado.edu)

| [<img src="https://avatars3.githubusercontent.com/u/30328854?v=4" width="60px;"/><br /><sub><b>John Letey</b></sub>](https://github.com/johnletey)<br />[💻](https://github.com/MUSSLES/tutorials/commits?author=johnletey "Code") | [<img src="https://avatars2.githubusercontent.com/u/13415542?v=4" width="60px;"/><br /><sub><b>Nihar Nandan</b></sub>](http://github.com/niharnandan)<br />[💻](https://github.com/MUSSLES/tutorials/commits?author=niharnandan "Code") | [<img src="https://avatars2.githubusercontent.com/u/35549559?v=4" width="60px;"/><br /><sub><b>Mingxuan Zhang</b></sub>](http://github.com/MingxuanZhang)<br />[💻](https://github.com/MUSSLES/tutorials/commits?author=MingxuanZhang "Code") | [<img src="https://avatars2.githubusercontent.com/u/19948806?v=4" width="60px;"/><br /><sub><b>Tony Wong</b></sub>](http://github.com/tonyewong)<br />[💻](https://github.com/MUSSLES/tutorials/commits?author=tonyewong "Code") |
| :---: | :---: | :---: | :---: |

## License

Copyright 2018 Tony Wong, H. Nihar Nandan, John Letey, Mingxuan Zhang

This file is part of MUSSLES (Modeling and Uncertainty in Storm and Sea LEvelS). MUSSLES is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

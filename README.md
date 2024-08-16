<br />
<a href="https://github.com/finos/perspective/blob/master/docs/static/svg/perspective-logo-light.svg?raw=true#gh-light-mode-only"><img src="https://github.com/finos/perspective/raw/master/docs/static/svg/perspective-logo-light.svg?raw=true#gh-light-mode-only" alt="Perspective" width="260"></a>
<a href="https://github.com/finos/perspective/blob/master/docs/static/svg/perspective-logo-dark.svg?raw=true#gh-dark-mode-only"><img src="https://github.com/finos/perspective/raw/master/docs/static/svg/perspective-logo-dark.svg?raw=true#gh-dark-mode-only" alt="Perspective" width="260"></a>
<br/><br/>

[![npm](https://img.shields.io/npm/v/@finos/perspective.svg?style=flat)](https://www.npmjs.com/package/@finos/perspective)
[![PyPI](https://img.shields.io/pypi/v/perspective-python.svg?style=flat)](https://pypi.python.org/pypi/perspective-python)
[![crates.io](https://img.shields.io/crates/v/perspective.svg?style=flat)](https://crates.io/crates/perspective)
[![Build Status](https://github.com/finos/perspective/actions/workflows/build.yaml/badge.svg?branch=master&event=push)](https://github.com/finos/perspective/actions/workflows/build.yaml)

<br/>

Perspective is an <i>interactive</i> analytics and data visualization component,
which is especially well-suited for <i>large</i> and/or <i>streaming</i>
datasets. Use it to create user-configurable reports, dashboards, notebooks and
applications, then deploy stand-alone in the browser, or in concert with Python
and/or [Jupyterlab](https://jupyterlab.readthedocs.io/en/stable/).

### Features

-   A fast, memory efficient streaming query engine, written in
    C++ and compiled for both [WebAssembly](https://webassembly.org/) and
    [Python](https://www.python.org/), with read/write/streaming for
    [Apache Arrow](https://arrow.apache.org/), and a high-performance columnar
    expression language based on [ExprTK](https://github.com/ArashPartow/exprtk).

-   A framework-agnostic User Interface packaged as a
    [Custom Element](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements),
    powered either in-browser via WebAssembly or virtually via
    WebSocket server (Python/Node).

-   A [JupyterLab](https://jupyter.org/) widget and Python client library, for
    interactive data analysis in a notebook, as well as _scalable_ production
    [Voila](https://github.com/voila-dashboards/voila) applications.

### Examples

<!-- Examples -->
<table><tbody><tr><td>editable</td><td>file</td><td>fractal</td></tr><tr><td><a href="https://perspective.finos.org/block?example=editable"><img height="125" src="https://perspective.finos.org/blocks/editable/preview.png?"></img></a></td><td><a href="https://perspective.finos.org/block?example=file"><img height="125" src="https://perspective.finos.org/blocks/file/preview.png?"></img></a></td><td><a href="https://perspective.finos.org/block?example=fractal"><img height="125" src="https://perspective.finos.org/blocks/fractal/preview.png?"></img></a></td></tr><tr><td>market</td><td>raycasting</td><td>evictions</td></tr><tr><td><a href="https://perspective.finos.org/block?example=market"><img height="125" src="https://perspective.finos.org/blocks/market/preview.png?"></img></a></td><td><a href="https://perspective.finos.org/block?example=raycasting"><img height="125" src="https://perspective.finos.org/blocks/raycasting/preview.png?"></img></a></td><td><a href="https://perspective.finos.org/block?example=evictions"><img height="125" src="https://perspective.finos.org/blocks/evictions/preview.png?"></img></a></td></tr><tr><td>nypd</td><td>magic</td><td>streaming</td></tr><tr><td><a href="https://perspective.finos.org/block?example=nypd"><img height="125" src="https://perspective.finos.org/blocks/nypd/preview.png?"></img></a></td><td><a href="https://perspective.finos.org/block?example=magic"><img height="125" src="https://perspective.finos.org/blocks/magic/preview.png?"></img></a></td><td><a href="https://perspective.finos.org/block?example=streaming"><img height="125" src="https://perspective.finos.org/blocks/streaming/preview.png?"></img></a></td></tr><tr><td>covid</td><td>webcam</td><td>movies</td></tr><tr><td><a href="https://perspective.finos.org/block?example=covid"><img height="125" src="https://perspective.finos.org/blocks/covid/preview.png?"></img></a></td><td><a href="https://perspective.finos.org/block?example=webcam"><img height="125" src="https://perspective.finos.org/blocks/webcam/preview.png?"></img></a></td><td><a href="https://perspective.finos.org/block?example=movies"><img height="125" src="https://perspective.finos.org/blocks/movies/preview.png?"></img></a></td></tr><tr><td>superstore</td><td>citibike</td><td>olympics</td></tr><tr><td><a href="https://perspective.finos.org/block?example=superstore"><img height="125" src="https://perspective.finos.org/blocks/superstore/preview.png?"></img></a></td><td><a href="https://perspective.finos.org/block?example=citibike"><img height="125" src="https://perspective.finos.org/blocks/citibike/preview.png?"></img></a></td><td><a href="https://perspective.finos.org/block?example=olympics"><img height="125" src="https://perspective.finos.org/blocks/olympics/preview.png?"></img></a></td></tr><tr><td>jupyterlab</td></tr><tr><td><a href="http://beta.mybinder.org/v2/gh/finos/perspective/master?urlpath=lab/tree/examples/jupyter-notebooks"><img height="125" src="https://perspective.finos.org/img/jupyterlab.png?"></img></a></td></tr></tbody></table>
<!-- Examples -->

### Documentation

-   [Project Site](https://perspective.finos.org/)
-   User Guides
    -   [Javascript User Guide](https://perspective.finos.org/docs/js.html)
    -   [Python User Guide](https://perspective.finos.org/docs/python.html)
    -   [Developer Guide](https://perspective.finos.org/docs/development.html)
-   Concepts
    -   [Table](https://perspective.finos.org/docs/table.html)
    -   [View](https://perspective.finos.org/docs/view.html)
    -   [Expression Columns](https://perspective.finos.org/docs/expressions.html)
    -   [Data Binding](https://perspective.finos.org/docs/table.html)
-   API
    -   [Perspective API](https://github.com/finos/perspective/blob/master/packages/perspective/README.md)
    -   [Perspective Viewer API](https://perspective.finos.org/docs/obj/perspective-viewer/)
    -   [Perspective Python API](https://perspective.finos.org/docs/obj/perspective-python.html)

### Community / Media

-   [Streaming, cross-sectional data visualization in JupyterLab | Junyuan Tan, JupyterCon 2020](http://www.youtube.com/watch?v=IO-HJsGdleE)
-   [Perspective in 3D | Andrew Stein, Open Source in Finance Forum NYC 2022](https://www.youtube.com/watch?v=0ut-ynvBpGI)
-   [Build an order book simulation with Perspective | Andrew Stein, FINOS Open Source in Fintech Meetup 2021](https://www.youtube.com/watch?v=no0qChjvdgQ)
-   [Perspective project case study | FINOS](https://www.finos.org/hubfs/FINOS/assets/FINOS%20Perspective%20Case%20Study.pdf)







# Blockchain Asset Tracking
A supply chain consists of many different participants exchanging goods, services, and payments. It is often desirable to track the physical assets digitally to be informed about the whereabouts, to trigger processes, certify the ownership, and perform corresponding payments.

The main four functions of this supply chain managment implementation is "Create Asset" , "Transfer Asset" ,"Search Asset" and "Delete Asset". also some minor functionalities include an event history of the four main functions and a login/signup/logout pages.

## Screenshots
### View Assets
![alt text](https://github.com/FirasHabri/Blockchain-Asset-Tracking/blob/master/screenshots/index.png)

### Create Asset
![alt text](https://github.com/FirasHabri/Blockchain-Asset-Tracking/blob/master/screenshots/create.png)

### Transfer Asset
![alt text](https://github.com/FirasHabri/Blockchain-Asset-Tracking/blob/master/screenshots/transfer.png)

### Delete Asset
![alt text](https://github.com/FirasHabri/Blockchain-Asset-Tracking/blob/master/screenshots/delete.png)

### Search Asset
![alt text](https://github.com/FirasHabri/Blockchain-Asset-Tracking/blob/master/screenshots/assetDetail.png)

## Getting Started
### Prequisites
  - PHP
  - XAMPP
  - Web3JS
  - MetaMask
  - Visual Studio Code "any IDE would do the trick"
  - Google Chrome " any Browser would do the trick too"

### Run
#### Install and Setup MetaMask
go to [MetaMask](https://metamask.io/download.html) to download the extention and create an account. Switch to Rinkebey Test Network and Deposite some Ether "Go to Test Faucet and hit Get Ether". Then go to Crypto Faucet and follow the instructions.

#### XAMPP
start XAMPP Apache server and MySQL and go to http://localhost/blockchain/index.html. Don't forget to move the files to xampp/htdocs/blockchain to not get an error!.

#### Remix Ethereum
If you want to edit the .sol Contracts you need to go to [Remix Ethereum](https://remix.ethereum.org/) . switch to Solidity enviroment and create two .sol files. AssetTracker.sol and AssetLibrary.sol, Then copy the content of the contracts from this git repo into the .sol files. don't forget to compile each file first. Then in the Deploy tab switch to Injected Web3 enviroment and hit Deploy.
To use your edited contracts in the repo go to js/ether_config.js and edit the address and abi variables. you can get the address from the deploy tab and the abi from the complie tab. "Do I need to tell you everything?"

## Authors
Me

## License
Free

## Acknowledgment
Big thanks to [ ilavisharma ](https://github.com/ilavisharma/Asset-Tracker-Blockchain) for providing the base code and contracts.







# Pixel2Mesh
This repository contains the TensorFlow implementation for the following paper</br>

[Pixel2Mesh: Generating 3D Mesh Models from Single RGB Images (ECCV2018)](http://openaccess.thecvf.com/content_ECCV_2018/papers/Nanyang_Wang_Pixel2Mesh_Generating_3D_ECCV_2018_paper.pdf)</br>

Nanyang Wang, [Yinda Zhang](http://robots.princeton.edu/people/yindaz/), [Zhuwen Li](http://www.lizhuwen.com/), [Yanwei Fu](http://yanweifu.github.io/), [Wei Liu](http://www.ee.columbia.edu/~wliu/), [Yu-Gang Jiang](http://www.yugangjiang.info/).

#### Citation
If you use this code for your research, please consider citing:

    @inProceedings{wang2018pixel2mesh,
      title={Pixel2Mesh: Generating 3D Mesh Models from Single RGB Images},
      author={Nanyang Wang and Yinda Zhang and Zhuwen Li and Yanwei Fu and Wei Liu and Yu-Gang Jiang},
      booktitle={ECCV},
      year={2018}
    }

# Try it on Colab

Installing all the dependencies might be tricky and you need a computer with a CUDA enabled GPU. To get started fast you can just try [this](https://colab.research.google.com/drive/13xkSkvPaF5GU6Wpf35nVHUdP77oBVHlT#scrollTo=xXxbMrF4fdZs) demo developed by [Mathias Gatti](https://github.com/mathigatti) using Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/13xkSkvPaF5GU6Wpf35nVHUdP77oBVHlT#scrollTo=xXxbMrF4fdZs)


# Project Page
The project page is available at https://nywang16.github.io/p2m/index.html

# Dependencies
Requirements:
* Python2.7+ with Numpy and scikit-image
* [Tensorflow (version 1.0+)](https://www.tensorflow.org/install/)
* [TFLearn](http://tflearn.org/installation/)

Our code has been tested with Python 2.7, **TensorFlow 1.3.0**, TFLearn 0.3.2, CUDA 8.0 on Ubuntu 14.04.

# News
- Nov. 8, we update the script for generate auxiliary data.

# Running the demo
```
git clone https://github.com/nywang16/Pixel2Mesh.git
cd Data/
```
Download the pre-trained model and unzip to the `Data/` folder.
* https://drive.google.com/file/d/1gD-dk-XrAa5mfrgdZSunjaS6pUUWsZgU/view?usp=sharing
```
unzip checkpoint.zip
```

#### Reconstructing shapes
    python demo.py --image Data/examples/plane.png
Run the demo code and the output mesh file is saved in `Data/examples/plane.obj` 

#### Input image, output mesh
<img src="./Docs/images/plane.png" width = "330px" /><img src="./Docs/images/plane.gif" />

# Installation

If you use CD and EMD for training or evaluation, we have included the cuda implementations of [Fan et. al.](https://github.com/fanhqme/PointSetGeneration) in external/

    cd Pixel2Mesh/external/

    Modify the first 3 lines of the makefile to point to your nvcc, cudalib and tensorflow library.

    make


# Dataset

We used the [ShapeNet](https://www.shapenet.org) dataset for 3D models, and rendered views from [3D-R2N2](https://github.com/chrischoy/3D-R2N2):</br>
When using the provided data make sure to respect the shapenet [license](https://shapenet.org/terms).

Below is the complete set of training data. Download it into the `Data/` folder.

https://drive.google.com/open?id=131dH36qXCabym1JjSmEpSQZg4dmZVQid </br>


The training/testing split can be found in `Data/train_list.txt` and `Data/test_list.txt` </br>
    
Each .dat file in the provided data contain: </br>
* The sampled point cloud (with vertex normal) from ShapeNet. We transformed it to corresponding coordinates in camera coordinate based on camera parameters from the Rendering Dataset.

**Input image, ground truth point cloud.**</br>
<img src="./Docs/images/car_example.png" width = "350px" />
![label](./Docs/images/car_example.gif)

# Training
    python train.py
You can change the training data, learning rate and other parameters by editing `train.py`

The total number of training epoch is 30; the learning rate is initialized as 3e-5 and drops to 1e-5 after 25 epochs.

# Evaluation
The evaluation code was released, please refer to `eval_testset.py` for more details.

Notice that the 3D shape are downscaled by a factor of 0.57 to generate rendering. As result, all the numbers shown in experiments used 0.57xRaw Shape for evaluation. This scale may be related to the render proccess, we used the rendering data from 3DR2N2 paper, and this scale was there since then for reason that we don't know.

# Statement
This software is for research purpose only. </br>
Please contact us for the licence of commercial purposes. All rights are preserved.

# Contact
Nanyang Wang (nywang16 AT fudan.edu.cn)

Yinda Zhang (yindaz AT cs.princeton.edu)

Zhuwen Li (lzhuwen AT gmail.com)

Yanwei Fu (yanweifu AT fudan.edu.cn)

Yu-Gang Jiang (ygj AT fudan.edu.cn)

# License
Apache License version 2.0





# Blockchain Developer Nanodegree project 3 (Supply chain )
This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

## Project write-up - UML

### Activity
![Activity](UML/Activity-Diagram.jpg)

### Sequence
![Sequence](UML/Sequence-Diagram.jpg)

### State
![State](UML/State-Diagram.jpg)

### Classes (Data Model)
![Data-Model](UML/Data-Model-Diagram.jpg)

## Project write-up - Libraries
The `Roles` library was used by different access control contracts for easy add and remove in the supply chain 
`truffle-hd-wallet-provider` to sign transactions for addresses.

## IPFS
IPFS is not used in this project

## Program Versions numbers
Node: v10.15.3
Solidity: v0.4.24
Truffle: v5.0.25
Web3.js: v1.0.0-beta37 

## Contract address on the Rinkeby test network (Etherscan):
https://rinkeby.etherscan.io/address/0x1d4396d3dfdfffb57e2ae580f175e7dfcf08759a

## Transaction ID and contract address

======================
> Network name:    'rinkeby'
> Network id:      4
> Block gas limit: 0x989677


1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0x1a02bb12fc80417e2ad1bd56250775110126d74e48fbb03041ae98b24ff92052
   > Blocks: 1            Seconds: 21
   > contract address:    0x302cfAe2e65F6651f3fDB5fAe6f635ca62CA567b
   > block number:        5625069
   > block timestamp:     1576515319
   > account:             0x1D4396D3DfdFFFB57e2Ae580f175E7DFCf08759A
   > balance:             0.97167573
   > gas used:            238594
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00238594 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.00238594 ETH


2_deploy_contracts.js
=====================

   Deploying 'FarmerRole'
   ----------------------
   > transaction hash:    0x79b84bba9672baeb0181fa97016e03510903903052a19f4a4a6f0168627ef9ca
   > Blocks: 1            Seconds: 12
   > contract address:    0xa041c902B5E6a8a83c9A3cf6D55C65183eb2462f
   > block number:        5625071
   > block timestamp:     1576515349
   > account:             0x1D4396D3DfdFFFB57e2Ae580f175E7DFCf08759A
   > balance:             0.96674205
   > gas used:            451020
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.0045102 ETH


   Deploying 'DistributorRole'
   ---------------------------
   > transaction hash:    0xf245353475ad170ce060d54680cb2003f8abf9ecdef52db245791b3ca9f79b41
   > Blocks: 0            Seconds: 9
   > contract address:    0xaf1624F9BA8972070eE42311684BE921000355b1
   > block number:        5625072
   > block timestamp:     1576515364
   > account:             0x1D4396D3DfdFFFB57e2Ae580f175E7DFCf08759A
   > balance:             0.96223113
   > gas used:            451092
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00451092 ETH


   Deploying 'RetailerRole'
   ------------------------
   > transaction hash:    0xec3342fef968e5791df950cf6e1ba8b037d348b11f26e8f5a58f2cb41e6523fe
   > Blocks: 0            Seconds: 9
   > contract address:    0xaf4Cb7bb1ED23FA76f18E34261BE81584Bc6c792
   > block number:        5625073
   > block timestamp:     1576515379
   > account:             0x1D4396D3DfdFFFB57e2Ae580f175E7DFCf08759A
   > balance:             0.95772033
   > gas used:            451080
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.0045108 ETH


   Deploying 'ConsumerRole'
   ------------------------
   > transaction hash:    0x0346a0f1176aacbc2f70d695d25d3ff0bc2b2c5b7b29257e530a3c63510a595a
   > Blocks: 0            Seconds: 7
   > contract address:    0x59Fb032D660d3830Ec24729D6A57286c8Cef0dd8
   > block number:        5625074
   > block timestamp:     1576515394
   > account:             0x1D4396D3DfdFFFB57e2Ae580f175E7DFCf08759A
   > balance:             0.95320977
   > gas used:            451056
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00451056 ETH


   Deploying 'SupplyChain'
   -----------------------
   > transaction hash:    0x33d25ff003526fa072304b4fcb2921d8e160c37b3cd70292d6a842cf6cecbb49
   > Blocks: 1            Seconds: 10
   > contract address:    0x66c0486577009EC26A9429B1E38657Ba0fa5c2B0
   > block number:        5625075
   > block timestamp:     1576515409
   > account:             0x1D4396D3DfdFFFB57e2Ae580f175E7DFCf08759A
   > balance:             0.92025103
   > gas used:            3295874
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.03295874 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.05100122 ETH


Summary
=======
> Total deployments:   6
> Final cost:          0.05338716 ETH

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Please make sure you've already installed ganache-cli, Truffle and enabled MetaMask extension in your browser.

```
Give examples (to be clarified)
```

### Installing

A step by step series of examples that tell you have to get a development env running

Clone this repository:

```
git clone https://github.com/udacity/nd1309/tree/master/course-5/project-6
```

Change directory to ```project-6``` folder and install all requisite npm packages (as listed in ```package.json```):

```
cd project-6
npm install
```

Launch Ganache:

```
ganache-cli -m "spirit supply whale amount human item harsh scare congress discover talent hamster"
```

Your terminal should look something like this:

![truffle test](images/ganache-cli.png)

In a separate terminal window, Compile smart contracts:

```
truffle compile
```

Your terminal should look something like this:

![truffle test](images/truffle_compile.png)

This will create the smart contract artifacts in folder ```build\contracts```.

Migrate smart contracts to the locally running blockchain, ganache-cli:

```
truffle migrate
```

Your terminal should look something like this:

![truffle test](images/truffle_migrate.png)

Test smart contracts:

```
truffle test
```

All 10 tests should pass.

![truffle test](images/truffle_test.png)

In a separate terminal window, launch the DApp:

```
npm run dev
```

## Built With

* [Ethereum](https://www.ethereum.org/) - Ethereum is a decentralized platform that runs smart contracts
* [IPFS](https://ipfs.io/) - IPFS is the Distributed Web | A peer-to-peer hypermedia protocol
to make the web faster, safer, and more open.
* [Truffle Framework](http://truffleframework.com/) - Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.


## Authors

See also the list of [contributors](https://github.com/your/project/contributors.md) who participated in this project.

## Acknowledgments

* Solidity
* Ganache-cli
* Truffle
* IPFS






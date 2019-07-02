# AI
1 add a convolution net

cmd for push to git hub:
git push -u origin master

install:
install miniconda
https://docs.conda.io/en/latest/miniconda.html
$ sh Miniconda3-latest-Linux-x86_64.sh
$ source ~/.bashrc

$ pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
$ conda env create -f environment.yml
the install package like install under ubuntu:

        $ sudo apt-get instll git

        $ sudo apt-get install build-essential

        $ sudo apt-get install libatlas-base-dev

        $ sudo apt-get install libopencv-dev

        $ sudo apt-get install graphviz

        $ sudo apt-get install python-numpy

        $ sudo apt-get install python-setuptools

        $ sudo apt-get install python-pip

        $ sudo pip install graphviz

        $ sudo pip install jupyter

        $ sudo pip install sklearn

        $ sudo pip install scipy

        $ sudo pip install opencv-python

        $ sudo pip install scikit-image

        $ sudo pip install easydict
        $ sudo pip3 install mxnet-cu80

        $ sudo pip3 install d2lzh
        $ sudo pip3 install notedown

note: we install in base, don't create new env, because some source download speed is slow.




git clone --recursive https://github.com/apache/incubator-mxnet mxnet

install pycharm, --setting,--project interpreter, select local python, plus available package, search mxnet-cu80 and install. 

install extension to caculate time in jupyter notebook.
pip install jupyter_contrib_nbextensions
jupyter contrib nbextension install --user
jupyter nbextension enable execute_time/ExecuteTime

cmd for change python3 version
sudo update-alternatives --config python3


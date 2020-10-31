# Python 2.7
#FROM tensorflow/tensorflow 
# 
#FROM tensorflow/tensorflow:nightly-py3-jupyter
FROM tensorflow/tensorflow


RUN apt update
RUN apt upgrade -y

RUN apt install vim -y
RUN apt install netutils* -y

RUN apt install python3-dev python3-pip
RUN pip install -U virtualenv  # system-wide install

RUN pip install --upgrade pip


RUN pip install jupyterlab
RUN pip install notebook


RUN pip install six numpy wheel
RUN pip install keras_applications==1.0.6 --no-deps
RUN pip install keras_preprocessing==1.0.5 --no-deps

RUN pip install matplotlib
RUN pip install Pillow
RUN pip install IPython

#RUN pip install https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow_cpu-2.1.0-cp37-cp37m-win_amd64.whl
# RUN pip uninstall tensorflow
# RUN pip install tensorflow
RUN pip install tensorflow_hub
RUN pip install tensorflow_datasets
RUN pip install ipywidgets
RUN pip install IProgress


RUN apt install bash* -y

#RUN jupyter notebook --port 8888 --no-browser

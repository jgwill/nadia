# Python 2.7
#FROM tensorflow/tensorflow 
# 
FROM tensorflow/tensorflow:nightly-py3-jupyter

RUN apt update
RUN apt upgrade -y

RUN apt install vim -y
RUN apt install netutils* -y


RUN pip install --upgrade pip


RUN  pip install jupyterlab
RUN pip install notebook


RUN pip install six numpy wheel
RUN pip install keras_applications==1.0.6 --no-deps
RUN  pip install keras_preprocessing==1.0.5 --no-deps

RUN pip install matplotlib
RUN pip install IPython

RUN pip install https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow_cpu-2.1.0-cp37-cp37m-win_amd64.whl

#RUN jupyter notebook --port 8888 --no-browser

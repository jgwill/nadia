#
FROM tensorflow/tensorflow 

RUN apt update
RUN apt upgrade -y

RUN apt install vim -y

RUN pip install --upgrade pip


RUN  pip install jupyterlab
RUN pip install notebook


RUN pip install six numpy wheel
RUN pip install keras_applications==1.0.6 --no-deps
RUN  pip install keras_preprocessing==1.0.5 --no-deps
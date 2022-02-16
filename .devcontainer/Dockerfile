FROM tensorflow/tensorflow:2.8.0rc1-gpu

# RUN pip3 install numpy pandas matplotlib seaborn statistics
RUN apt-get install -y git vim htop
COPY requirements.txt /root/requirements.txt
RUN pip install -r /root/requirements.txt
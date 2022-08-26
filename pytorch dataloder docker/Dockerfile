FROM python:3

WORKDIR /usr/src/app

COPY requirements.txt .
COPY rsp_all_valid.csv .
COPY rsp_all.csv .

COPY dock_ex.py .
COPY load_ex.py .


RUN mkdir -p /rps/
RUN mkdir -p /rps_val/
ADD ./rps/ /rps/
ADD ./rps_val/ /rps_val/

RUN pip install numpy pandas torchvision torch matplotlib Pillow

CMD ["python", "./dock_ex.py"] 
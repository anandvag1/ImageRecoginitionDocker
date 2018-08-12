FROM python:3.6
WORKDIR /usr/src/app
COPY requirements.txt ./
COPY requirement1.txt ./
RUN pip install --no-cache-dir -r requirements.txt
RUN pip3 install --no-cache-dir -r requirement1.txt
COPY . .
CMD [ "python", "app.py" ]

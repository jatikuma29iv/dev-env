FROM python:3

RUN pip install jupyterlab

WORKDIR /app

EXPOSE 8888

# CMD ["sleep", "infinity"]

CMD ["jupyter", "lab", "--allow-root","--ip", "0.0.0.0"]

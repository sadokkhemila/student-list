FROM python:2.7-stretch
MAINTAINER POZOS
ADD student_age.py /
RUN pip install flask
VOLUME [ "/data" ]
EXPOSE 5000
CMD [ "python", "./student_age.py" ]

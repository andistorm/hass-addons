ARG BUILD_FROM
FROM $BUILD_FROM

# Copy data for add-on
COPY main.py /
RUN chmod a+x /main.py

CMD [ "python3 /main.py" ]

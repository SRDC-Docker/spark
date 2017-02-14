FROM srdc/scala:2.10.6
MAINTAINER SRDC Corp. <technical@srdc.com.tr>

ENV SPARK_VERSION 1.6.0

RUN curl http://archive.apache.org/dist/spark/spark-$SPARK_VERSION/spark-$SPARK_VERSION-bin-hadoop2.6.tgz | tar -xz -C /opt
RUN cd /opt && ln -s ./spark-$SPARK_VERSION-bin-hadoop2.6 spark

ENV SPARK_HOME /opt/spark
ENV PATH $SPARK_HOME/bin:$PATH

CMD ["bash"]

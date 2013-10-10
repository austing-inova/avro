Apache Avro™ is a data serialization system.

Learn more about Avro, please visit our website at:

  http://avro.apache.org/

To contribute to Avro, please read:

  https://cwiki.apache.org/AVRO/how-to-contribute.html



** This forked repository has been modified to add Python 3.x compatability to Avro, so far, the following files have been fixed:
schema.py
io.py
datafile.py


The associated tests for these files were also fixed and are passing.

Also moved the setup.py file into the base directory so that the module can be pip installed via:
pip install git+git://github.com/austing-inova/avro.git@trunk#egg=avro

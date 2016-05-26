# About
This respository contains code for the course project for ETH Zurich's 
spring 2016 NLP course, and implements an entity linking system for queries.

Usage:
Predict queries(from xml): [Contact Qin
python ./runme.py ***.xml
It will generate a output.txt in the current directory that contains the linking results.

The FinalJAVA directory contains the codes that read from a output file and work as an annotator under the JAVA framework. [Contact Jakob

Three dependencies:
Numpy, Theano,  python-Levenshtein

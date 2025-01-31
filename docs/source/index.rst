CSE524: Accelerator Design Lab 2
===================================

Welcome to Lab 2 of the Accelerator Design class. In this lab, we are going to be optimizing the BERT model using OpenVINO, a deployment and inferencing tool from Intel used to test and optimize ML models.

Objective of this Lab
--------------

The BERT transformer model studied in the class was one of the most influential models created in recent years, introducing a new architecture that made Natural Language Processing a much simpler task. The drawback however is the fact that the model is heavy because of the transformer, and takes up a lot of compute power, making it difficult to execute without using a GPU. We are given the BERT model and the xyz dataset. Though it performs well, the aim is to try and optimize it using techniques such as quantization and pruning to reduce the size of th model whille preserving the original efficiency. 

.. note::

   The submission deadline for this lab is 00/00/2025. 

Contents
--------

.. toctree::
   :maxdepth: 2

   Tiber_Setup
   Console_guide
   Jupyter

.. Copyright 2019 <Huawei Technologies Co., Ltd>

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

.. title:: Overview

Huawei HiQ
==========

Huawei HiQ is an open-source software framework for quantum computing. It aims at providing tools which facilitate **inventing**, **implementing**, **testing**, **debugging**, and **running** quantum algorithms using either classical hardware or actual quantum devices.

#. **Open development system**: *Huawei HiQ is released under the* **Apache 2** *license. The framework is based on and compatible with open-source ProjectQ software and will continue to be open-source*
#. **Visualization scheme for classical-quantum hybrid programming**: *Unique quantum programming BlockUI makes classical-quantum hybrid programming easy and intuitive*
#. **Support of distributed and scalable hardware and software**: *The compilation framework supports multi-type of quantum hardware backends and Python/C++ API front-end extensions*
#. **Outstanding computational performance**: *Provides high-performance C++ parallel and distributed simulator backends*
#. **High-efficient resource management**: *Integrated high-performance optimizer for quantum circuit compiling to support finite internal RAMs and massively parallel computing*
#. **Support with rich algorithm library and help documents**: *Rich algorithm Library of important basic algorithms, accelerates the learning and development processes*


Please cite
	* Huawei HiQ team, "Huawei HiQ: A High-performance Quantum Computing Simulator and Programming Framework", http://hiq.huaweicloud.com.


Contents
	* :ref:`QuantumComputing`: Introduction to the basic concepts of quantum computing
	* :ref:`tutorials`: Tutorial containing instructions on how to get started with Huawei HiQ
	* :ref:`examples`: Example implementations of few quantum algorithms

.. toctree::
   :caption: INSTALLATION
   :maxdepth: 2

   installation

.. toctree::
   :caption: QUANTUM COMPUTING
   :maxdepth: 2

   quantumcomputing
   tutorials
   examples

.. toctree::
   :caption: API REFERENCE
   :maxdepth: 2
   
   api/python
   api/cxx

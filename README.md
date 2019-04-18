# qoogleWB
Qoogle Workbench is a Python 3 software Workbench for optimization and machine learning of quantum and hybrid quantum-classical computations.
Qoogle Workbench is a Python 3 software Workbench for optimization and machine learning of quantum and hybrid quantum-classical computations. The library provides a unified architecture for near-term quantum computing devices, supporting both qubit and continuous-variable paradigms. 

Qoogle Workbench’s core feature is the ability to compute gradients of variational quantum circuits in a way that is compatible with classical techniques such as backpropagation. Qoogle Workbench thus extends the automatic differentiation algorithms common in optimization and machine learning to include quantum and hybrid computations. A plugin system makes the Workbench compatible with any gate-based quantum simulator or hardware. We provide plugins for Strawberry Fields, Rigetti Forest, Qiskit, and ProjectQ, allowing Qoogle Workbench optimizations to be run on publicly accessible quantum devices provided by Rigetti and IBM Q. 

On the classical front, Qoogle Workbench interfaces with accelerated machine learning libraries such as TensorFlow, PyTorch, and autograd. Qoogle Workbench can be used for the optimization of variational quantum eigensolvers, quantum approximate optimization, quantum machine learning models, and many other applications.

Product Vision

We will introduce Qoogle Workbench, a Python package that extends automatic differentiation to quantum and hybrid classical-quantum information processing. This is accomplished by introducing a new quantum node abstraction which interfaces cleanly with existing DAG-based automatic differentiation methods like the backpropagation al-
gorithm. The ability to compute gradients of variational quantum circuits – and to integrate these seamlessly as part of larger hybrid computations – opens up a wealth of potential applications, in particular for optimization and machine learning tasks.

We envision Qoogle Workbench as a powerful tool for many research directions in quantum computing and quantum machine learning, similar to how libraries like TensorFlow or PyTorch have become indispensible for research in deep learning. With small quantum processors becoming publicly available, and with the emergence of variational quantum circuits as a new algorithmic paradigm, the quantum computing community has begun to embrace heuristic algorithms more and more. This spirit is already common in the classical machine learning community and has – together with dedicated software enabling rapid exploration of computational models – allowed that field to develop at a remarkable pace. 

With Qoogle Workbench, tools are now freely available to investigate model structures, training strategies, and optimization landscapes within hybrid and quantum machine learning, to explore existing and new variational circuit architectures, and to design completely new algorithms by circuit learning.

Product Overview

Recent progress in the development and commercialization of quantum technologies has had a profound impact on the landscape of quantum algorithms.

Near-term quantum devices require routines that are of shallow depth and robust against errors. The design paradigm of hybrid algorithms which integrate quantum and classical processing has therefore become increasingly important. Possibly the most well-known class of hybrid algorithms is that of variational circuits, which are parameter-dependent quantum circuits that can be optimized by a classical computer with regards to a given objective. Hybrid optimization with variational circuits opens up a number of new research avenues for near-term quantum computing with applications that require:

•	quantum optimization

•	factoring

•	state diagonalization

•	quantum machine learning

In a reversal from the usual practices in quantum computing research, a lot of research for these mostly heuristic algorithms necessarily focuses on numerical experiments rather than rigorous mathematical analysis. Luckily, there are various publicly accessible platforms to simulate quantum algorithms or even run them on real quantum devices through a cloud service. However, even though some frameworks are designed with variational circuits in mind there is at this stage no unified tool for the hybrid optimization of quantum circuits across quantum platforms, treating all simulators and devices on the same footing. 

Qoogle Workbench is an open-source Python 3 Workbench that facilitates the optimization of quantum and hybrid quantum-classical algorithms. It extends several seminal machine learning libraries — including autograd, TensorFlow and PyTorch — to handle modules of quantum information processing. This can be used to optimize variational quantum circuits in applications such as quantum approximate optimization, variational quantum eigensolvers. 

The Workbench can also handle more complex machine learning tasks such as training a hybrid quantum-classical machine learning model in a supervised fashion, or training a generative adverserial network, both when discriminator and generator are quantum models and when one is quantum and the other is classical, Qoogle Workbench can in principle be used with any gate-based quantum computing platform as a backend, including both qubit and continuous-variable architectures, and has a simple Python-based user interface.

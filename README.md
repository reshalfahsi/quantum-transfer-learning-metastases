# Quantum Transfer Learning for Lymph Node Metastases Detection


<div align="center">
    <a href="https://colab.research.google.com/github/reshalfahsi/quantum-transfer-learning-metastases/blob/master/Quantum_Transfer_Learning_for_Lymph_Node_Metastases_Detection.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="colab"></a>
    <br />
</div>


<p align="center"> <img src="https://github.com/reshalfahsi/quantum-transfer-learning-metastases/blob/master/assets/quantum-googlenet.png" alt="quantum-googlenet" > <br /> The Quantum GoogLeNet model. The quantum layer: the QAOA-inspired ansatz embedding, the particle-conserving entangler, and the expectation value of the Pauli Z operator. </p>


Transfer learning may make training on a particularly distinguishable dataset easier. It enables several elements of a pre-trained model to be used as the foundation of a new model's architecture. More importantly, we can adopt this approach in quantum machine learning as well. In this project, we seek to implement quantum transfer learning using an ImageNet-pre-trained model, which will be used on the PCam dataset to tackle the lymph node metastases detection problem. The pre-trained model is GoogLeNet, and the classifier uses hybrid classical-quantum fully connected layers. Typically, quantum layers are made up of embedding, quantum circuits, and measurement. The embedding and quantum circuits are built upon the QAOA-inspired ansatz and particle-conserving entangler, respectively.


## Experiment

Consider exploring this [notebook](https://github.com/reshalfahsi/quantum-transfer-learning-metastases/blob/master/Quantum_Transfer_Learning_for_Lymph_Node_Metastases_Detection.ipynb) to conduct the experiment by yourself.


## Result

## Quantitative Result

The quantitative results are outlined in the following table.

Test Metric | Score |
----------- | ----- |
Accuracy | 80.29%
Loss | 0.464


## Accuracy and Loss Curves

<p align="center"> <img src="https://github.com/reshalfahsi/quantum-transfer-learning-metastases/blob/master/assets/loss_curve.png" alt="loss_curve" > <br /> The model's loss curve on the train and validation sets. </p>

<p align="center"> <img src="https://github.com/reshalfahsi/quantum-transfer-learning-metastases/blob/master/assets/acc_curve.png" alt="acc_curve" > <br /> The model's accuracy curve on the train and validation sets. </p>


## Qualitative Result

This 3×3 image grid presents the qualitative result.

<p align="center"> <img src="https://github.com/reshalfahsi/quantum-transfer-learning-metastases/blob/master/assets/qualitative.png" alt="qualitative" > <br /> . </p>


## Citation

If you find this repository useful for your research, please cite it:

```
@misc{quantum-transfer-learning-metastases,
   title = {Quantum Transfer Learning for Lymph Node Metastases Detection},
   url = {https://github.com/reshalfahsi/quantum-transfer-learning-metastases},
   author = {Resha Dwika Hefni Al-Fahsi},
}
```


## Credit

- [Going deeper with convolutions](https://arxiv.org/pdf/1409.4842)
- [PatchCamelyon (PCam)](https://github.com/basveeling/pcam)
- [Rotation Equivariant CNNs for Digital Pathology](https://arxiv.org/pdf/1806.03962)
- [Transfer learning in hybrid classical-quantum neural networks](https://arxiv.org/pdf/1912.08278)
- [Quantum embeddings for machine learning](https://arxiv.org/pdf/2001.03622)
- [Quantum algorithms for electronic structure calculations: particle/hole Hamiltonian and optimized wavefunction expansions](https://arxiv.org/pdf/1805.04340)
- [PennyLane: Automatic differentiation of hybrid quantum-classical computations](https://arxiv.org/pdf/1811.04968)
- [Turning quantum nodes into Torch Layers](https://pennylane.ai/qml/demos/tutorial_qnn_module_torch)
- [PyTorch Lightning](https://lightning.ai/docs/pytorch/latest/)

# Quantum Transfer Learning with BERT

This is largely adapted from this [tutorial](https://pennylane.ai/qml/demos/tutorial_quantum_transfer_learning.html).

Instead of using ResNet on the Hymenoptera dataset, I adapted it for BERT on GLUE.

The model uses a classical pretrained model (BERT) and finetunes a quantum circuit on the GLUE dataset using the BERT embeddings. The BERT model has its weights frozen for simplicity.

# Libraries used
- [PyTorch](https://github.com/pytorch/pytorch) for the BERT model
- [🤗 Transformers](https://github.com/huggingface/transformers) for the BERT model
- [🤗 Datasets](https://github.com/huggingface/datasets) for the GLUE dataset
- [Pennylane](https://github.com/PennyLaneAI/pennylane) for the Quantum circuit

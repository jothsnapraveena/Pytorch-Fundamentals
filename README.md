🧠 PyTorch Neural Network Training Fundamentals
A hands-on PyTorch notebook I created while learning from the Build a Large Language Model from Scratch book. This notebook is designed to help anyone — especially beginners — understand how neural networks are trained step-by-step using PyTorch.

📌 What's Inside
This notebook covers the core building blocks of training a neural network:

✅ Tensor Basics
Tensor creation: 0D, 1D, 2D, and 3D

Data types and conversions (.to())

Reshaping, transposing, and tensor operations (.reshape, .view, .T, @)

✅ Autograd & Computational Graphs
Understanding requires_grad

Manual and automatic gradient computation

loss.backward() and torch.autograd.grad()

✅ Neural Network from Scratch
Custom neural network using torch.nn.Module

Forward propagation and Sequential API

Counting trainable parameters

Using .eval() and with torch.no_grad()

✅ Dataloaders & Training
Custom Dataset class

Batching with DataLoader

Training loop with loss and optimizer

Evaluation loop and accuracy metrics

✅ Model Saving & Loading
Saving using torch.save(model.state_dict(), ...)

Restoring with load_state_dict

🚀 Why This Exists
I built this as part of my foundational learning to build LLMs from scratch. 

If you're getting started with PyTorch or want to solidify your understanding of neural network internals, this will help.





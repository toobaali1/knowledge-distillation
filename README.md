# Knowledge Distillation on Fashion-MNIST

This project demonstrates knowledge distillation by training a CNN teacher model and a compact MLP student model on the Fashion-MNIST dataset. 

We trained:
- A teacher CNN for high-accuracy classification
- A small student MLP from scratch
- A distilled student trained using the teacher's softened logits

The distilled student achieves better performance than the scratch student, showing the effectiveness of knowledge distillation.

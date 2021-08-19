# IE-643-Implementation
Researchers across the world have come up with a large number of Deep Neural Networks to perform different tasks. However, the main concern about all those models is the large number of parameters that need to be trained to perform the task keeping in mind the risk of overfitting. Now for
training those large number of parameters, it not only requires vast computation capacity, and it also
requires a considerable amount of time. The research paper mainly tries to solve this question of overparametrization through pruning.
Different researchers have researched on the topic of pruning neural networks and has stuck to the
question that, can the sparse model be trained from scratch or not. In this research, the authors have
suggested a method to obtain a pruned network which can be trained in isolation to attain a commensurate accuracy. In the proposed method, they first initialized the network, trained it from some
epochs to get a considerable accuracy and then performed unstructured pruning. Then, they reinitialized the unpruned model weights and retrained it. They performed this process recursively to obtain
a subnetwork with a lesser number of parameters than the initial network model but have the same or
better accuracy.
By applying their proposed technique, they have demonstrated a considerable number of significant
results on the MNIST and CIFAR-10 dataset. They have worked on different convolutional architectures like LeNet, Conv-2/4/6. Their method has shown to have extensively high accuracies even when
only 10-20 percent of original weights remain.
In this report, Substantiated the existence of a significantly pruned network having comparable accuracy with original network and validated the hypothesis over LeNet and Feed Forward MLP networks on MNIST,
2. Considered the plausibility of transfering lottery tickets obtained from a dataset to another in same domain
Implementation of the Lottery Ticket Hypothesis - Finding Sparse Trainable Network for fulfillment of the IE 643 Course project<br>
and also considering Three different tasks as discussed in <a href='https://drive.google.com/file/d/1Lv7ukWuEooigreEBVW4hDA0vQzLBpz1C/view?usp=sharing'>report</a>
Code got from consulting following repository:
<ul>
  <li><a href='https://github.com/ktkth5/lottery-ticket-hyopothesis'>Repository 1</a>
  <li><a href='https://github.com/rahulvigneswaran/Lottery-Ticket-Hypothesis-in-Pytorch'>Repository 2</a> 
</ul>
Project done by 
1. Abhishek Narayan Chaudhury 19i190005
2. Saptarshi Majumdar 19i190011
3. Subhadeep Chaudhuri 19i190010

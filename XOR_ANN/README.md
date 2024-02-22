# XOR_DNN

Understanding how ANNs work, XOR gate model performed
with using simple ANN in Figure 3.
For solving xor problem, we used a simple neural network
model. The model has two neuron hidden layer and one neuron
output layer. Problem needs two decision plane that is why we
need two neurons in hidden layer. We chose sigmoid activation
function for every neuron’s activation function. Our problem
has two probable outcome zero and one. We chose sigmoid

function because it generates output between zero and one and
also function is differentiable. If we have multiclass problem,
we can choose softmax function against sigmoid function.

![image](https://github.com/oktayogutcu/ml_projects/assets/46667326/6d933de3-1670-43f2-b6cb-931b9e07807c)
Fig. 3. XOR problem.


<img width="139" alt="image" src="https://github.com/oktayogutcu/ml_projects/assets/46667326/7e49dafd-0418-4027-8139-88f08c5f1cb5">


![image](https://github.com/oktayogutcu/ml_projects/assets/46667326/17fa212d-cde7-497b-8531-bbcb68b8f410)
Fig. 4. Sigmoid function.

Loss function is chosen as square error loss which makes
our calculation of its ease to differentiate.
<img width="136" alt="image" src="https://github.com/oktayogutcu/ml_projects/assets/46667326/8a39add7-7487-46d0-aeb2-0119345fc405">


![image](https://github.com/oktayogutcu/ml_projects/assets/46667326/368cab66-f645-4376-ba30-2d95f2ea4795)
Fig. 5. ANN designed for XOR problem.


![image](https://github.com/oktayogutcu/ml_projects/assets/46667326/ecf6a5fb-e286-4e3e-84a8-53d18e4ed909)
Fig. 6. Loss graph for learning rate = 0.1.

![image](https://github.com/oktayogutcu/ml_projects/assets/46667326/86aeba06-9270-48bf-a163-f0f29bce0d92)
Fig. 7. Predicted output graph for learning rate = 0.1.

![image](https://github.com/oktayogutcu/ml_projects/assets/46667326/41bf46c6-4deb-41b4-b3a9-01c5ea9fcf5d)
Fig. 8. Loss graph for learning rate = 1.

![image](https://github.com/oktayogutcu/ml_projects/assets/46667326/ec6c39df-fa0b-4138-aab1-d75da8b017fe)
Fig. 9. Predicted output graph for learning rate = 1.

While training operations being done, batch gradient descent
performed with different learning rates. After backward and
forward passes performed, it is repeated 10.000 times. After
training operation done following results.
In Figure 7, predicted outputs plotted against every epoch in
training operation. As seen this figure training operation almost
converged after approximately 8000 epochs with learning
rate 0.1. After changing learning rate, it can be seen model
converged approximately 2000 epochs.






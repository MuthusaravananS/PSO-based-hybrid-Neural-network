# PSO-based-hybrid-Neural-network

cite this article, 

Efficient removal of antidepressant Flupentixol using graphene
oxide/cellulose nanogel composite: Particle swarm algorithm
based artificial neural network modelling and optimization
K. Balasubramani, N. Sivarajasekar, S. Muthusaravanan, K. Ram,
Mu. Naushad, Tansir Ahamad, Gaurav Sharma
PII: S0167-7322(20)35406-4
DOI: https://doi.org/10.1016/j.molliq.2020.114371
Journal of Molecular Liquids


Swarm based neural network for predicting adsorption percentage or adsorption capacity from process parameters.  
Initially, the PSO algorithm-based ANN reads input and target data from the user to create a 
feed  forward  neural network of size ‘n’. The following steps were implemented to train the developed 
feed forward ANN using PSO.  


i)  Initialization of particle population in PSO with position and velocity  


ii) Evaluation of initial fitness of each particle to find personal experience (Pbest) and overall experience 
(Gbest) 


iii) Setting the iteration count K=1   


iv) Update the position and velocity of each particle in PSO  


v) Evaluate the fitness of each particle and update Gbest and Pbest 


vi) Check the K value if K <= Maxite then K = k+1 and if not print the optimal weights and bias to ANN.  

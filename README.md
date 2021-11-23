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
The parameters such as overall experience (Gbest), personal experience (Pbest), and the present 
movement  of  the  particles  are  to  decide  the  updated  position  of  particles  in  multidimensional  search 
space. 
The  accuracy  of  the  developed  model  can  be  improved  by  parameter  tuning.  Furthermore,  the  PSO 
parameters  such  as  personal  learning  coefficient  (c1),  global  learning  coefficient  (c2),  swarm  population 
(Spop),  and  inertia  weight  (w)  must  be  optimized  for  the  initialization  of  the  algorithm.  The  improper setting  of  the  parameters  could  result  in  divergent  or  cyclic  behavior.  For  ANN,  the  parameters  such  as 
neural  network  type,  number  of  neurons  in  the  hidden  layers  (n)  were  selected  and  optimal  parameters 
were  identified.  The  performance  of  both  algorithms  was  further  improved  with  a  sensitivity  analysis 
approach by varying parameters such as c1, c2, and Spop. 
The  optimal  Spop  values  were  selected  based  on  the  performance  analysis.  To  determine  the  optimum 
value  of  the  acceleration,  factor  a  novel  sensitivity  analysis  approach  was  performed  for  the  data  by 
keeping  the  optimal  Spop  and a constant  value for ‘n’.  Finally, the optimal number of neurons in  the 
hidden  layer  was  obtained  by  considering  the  optimum  value  for  c1,  c2,  and  Spop. The value for ‘w’ was 
selected as  a random number in the range of 0-1. The performance of sensitivity analysis was evaluated 
based on the mean square error (MSE) and root mean square error (RMSE). The optimal Parameters for 
the PSO algorithm-based ANN model were obtained by performing trial and error experiments and used 
for simulating the test data. Few combinations of c1, c2, and Spop have been tried for different ‘n’ obtaining 
the optimal combination of PSO and ANN parameters. The termination criteria were set to be a maximum 
of 1000 iteration and improvement in the objective function (< 10−8) for 100 successive iterations. 

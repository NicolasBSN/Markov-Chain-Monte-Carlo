# Markov-Chain-Monte-Carlo

The reposotiry contains a first lab about the different algorithms studied in class.
</br>
**Markov chain Monte Carlo (MCMC)** methods are a class of algorithms for sampling from a probability distribution. By constructing a Markov chain that has the desired distribution as its invariant distribution, we can obtain a sample of the desired distribution by recording states from the chain. The more steps that are included, the more closely the distribution of the sample matches the actual desired distribution. Various algorithms exist for constructing chains and we implemented these ones :
- Metropolis-Hastings (MH) :
  - MH with a random walk
  - MH Adjusted Langevin algorithm
- Hamiltoninan Monte-Carlo (HMC) :
  - Leapfrog Integrator
  - Euler Integrator

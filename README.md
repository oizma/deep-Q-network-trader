# deep-Q-network-trader

A rudimentary implementation of a 5-layered neural network trained using reinforcement learning to produce buy, sell, and hold signals at each time step.

## Dependencies

For CPU support only:

    pip3 install --upgrade tensorflow

For GPUs with CUDA Compute Capability 3.0 or higher:

	pip3 install --upgrade tensorflow-gpu

For fetching historic data:

    pip install gdax-api

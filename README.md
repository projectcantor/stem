# stem
Neural network solver service. This service makes use of the patent algorithm to solve the differential equation as per the client request. Stem also maintains communication with tars (the caching service) to deliver the solution faster. If tars fails to give a desired output, a new nueral network architecture is used to solve the differential equation.

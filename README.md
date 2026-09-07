# test-blackscholes

This lecture by Vasily Strela from the MIT 18.642 course focuses on Risk-Neutral Valuation and the Black-Scholes formula as powerful frameworks for derivative pricing.

Key concepts covered in the lecture:
Market Dynamics and Replication: The instructor explains how derivatives can be priced by constructing a replicating portfolio (a mix of cash and underlying assets) that eliminates risk. This approach demonstrates that derivative prices depend on volatility and interest rates rather than investors' subjective risk preferences (0:16-10:21).
Forwards and Options: The lecture provides a breakdown of how to price simple derivatives like forwards, call options, and put options using both discrete-time models (10:53-34:25) and continuous-time stochastic calculus (34:35-59:53).
The Black-Scholes Equation: Through the application of Ito's Lemma (47:48), the instructor derives the Black-Scholes partial differential equation. This equation shows how the value of a derivative evolves over time and provides a basis for hedging strategies (1:02:45-1:03:32).
Risk-Neutral Measure: The lecture clarifies that in a risk-neutral world, the expected return of an asset equals the risk-free rate, allowing for the use of simpler expected-value calculations for pricing (1:06:22-1:10:29).
Put-Call Parity: The class concludes with an empirical demonstration of Put-Call Parity using market data from stocks like Apple and IBM, illustrating that the relationship between call and put prices is independent of the underlying stock's specific price dynamics (1:10:46-1:16:24).
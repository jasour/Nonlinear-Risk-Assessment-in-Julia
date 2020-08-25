
# Nonlinear-Risk-Assessment in Julia (moment SDP Formulation)

This solves the moment SDP to calculate the Risk. 
We use the solution of the dual SDP to calculate the risk. Solution of the dual SDP is the coefficients of the polynomial indicator function.

To run the codes you need the following packages in Julia:

1) MomentOpt julia package by Tillmann Weisser: Pkg.add("MomentOpt")
2)  SDP solvers like "mosek":  Pkg.add("MosekTools")
3) DynamicPolynomials: Pkg.add("DynamicPolynomials")


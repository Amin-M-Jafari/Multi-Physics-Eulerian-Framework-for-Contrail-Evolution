Description:
The .zip file contains two animations:
y-z_projection_500meter_ISSR_20percent_rand
y-z_projection_500meter_ISSR
Both simulations use the same initial conditions:
Temperature: T = 212 K
ISSR thickness: 500 m (100 m above and 400 m below the reference altitude)
Constant supersaturation: sᵢ = 0.2 (20%)
Synthetic initial geometry and particle radius
The only difference between the two cases is that the rand version includes 20% white Gaussian noise added to the sᵢ equation at each iteration, whereas the other simulation does not include stochastic perturbations.
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
Description:
The two .gif files: Tube_solver_horizontal_view & Tube_solver_vertical_view
are part of ongoing/future work and demonstrate the applicability of the present model to realistic, large-scale simulations.

Notes:
The animations were generated under synthetic atmospheric conditions with:
Supersaturation: sᵢ = 0.2 (20%)
Temperature: T = 212 K
Wind fields were derived directly from ERA5, using the modeling framework described in the paper.

In these simulations:
Supersaturation (sᵢ) is horizontally uniform.
sᵢ varies only in the vertical direction, reaching supersaturation level.
The aircraft is assumed to fly for a prescribed duration within the ISSR.
The tube-based solver tracks contrail evolution for approximately 15 hours.

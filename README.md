# RTHS_benchmark_SMC
Matlab code for the paper "Sliding mode control design for the benchmark problem in real-time hybrid simulation"
1. Run Actuator_id.m to plot the frequency response of the orignal and reduced models of the control plant.
1. Run main.m to get Evaluation criteria of SMC.
2. Run main_PI.m to get Evaluation criteria of PI-P.
3. Run Elcentro_results.m to plot the responses under El Centro earthquake.

Note that the designated displacement, velocity and acceleration (all relative to the ground) of the physical substructure are required for the Sliding mode controller. However the original released code of the benchmark problem only gives designated displacement. Additional operations to obtain designated velocity and acceleration from the numerical substructure are added/modified and marked in F1_input_file.m and vRTHS_MDOF_SimRT.slx.

If you have any problems, please contact hongweili@seu.edu.cn

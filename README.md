# Fuzzy_Logic_Adaptive_Optimal_Regulator
This passage provides a professional and technical description of your adaptive optimal regulator for active vibration control, specifically highlighting its role in suppressing disturbances like white noise.
Active Vibration Control via Fuzzy-Adaptive LQR
This repository implements an Active Vibration Control (AVC) strategy using a Fuzzy-Adaptive Linear Quadratic Regulator (LQR) for high-performance vibration suppression. Unlike conventional fixed-gain LQR controllers, which may struggle with unpredictable environmental uncertainties, this regulator utilizes a Fuzzy Inference System (FIS) to adaptively tune the LQR weighting matrices ($Q$ and $R$) or the system's degree-of-stability in real-time.
Key technical features include:

* Zero Reference Tracking (Regulator Mode): The controller operates in a pure regulator configuration, focused entirely on minimizing state deviations ($x \to 0$) rather than tracking an external reference.
* Active Disturbance Rejection: The system is specifically designed to mitigate external white noise disturbances, simulating stochastic environmental excitations common in mechanical and structural systems.
* Adaptive Optimal Control: By leveraging fuzzy logic to relocate closed-loop eigenvalues or adjust gain parameters, the regulator maintains an optimal balance between vibration attenuation and control effort under time-varying conditions.
* Vibration Suppression Performance: The adaptive law enhances transient recovery and reduces Root-Mean-Square (RMS) acceleration, providing a more robust solution than traditional PID or static LQR controllers for complex engineering scenarios.

Would you like to include a performance comparison table or a block diagram description to further illustrate the controller's architecture?


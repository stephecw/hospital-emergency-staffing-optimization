# hospital-emergency-staffing-optimization
This project explores how to optimize staffing and patient flow in hospital emergency departments as part of the URGE research program (Inria × AP-HP). With overcrowded emergency rooms and limited medical staff, improving resource allocation is essential.

We developed:
	•	Mathematical models of patient flow using Timed Petri Nets to represent consultations, staff roles, and system dynamics.
	•	A steady-state analysis to estimate the maximum number of patients that can be treated based on the number of interns, senior doctors, and consultation times.
	•	An optimization approach to staffing, formulated as an integer linear program considering legal work constraints and scheduling rules.
	•	Crisis simulations (sudden or prolonged influxes of patients) to study queue growth and evaluate strategies for reallocating staff.

Although some models remain theoretical, this work provides a solid foundation for data-driven staffing decisions and emergency department planning.

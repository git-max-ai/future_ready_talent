# Quantum simulation of Heisenberg spin model

Here we apply Hamiltonian quantum dynamics for simulation of 3 qubits spin model our overall
simulation is unitary but we can try for any state or pair of state for specified time period, we use trotter
Suzuki method to decompose circuit in 10 trotter steps for accurate simulation, first we simulate using
classical method after that we have define quantum sub-circuit for simulation of 2-2 qubits pairs and
finally append sub-circuit to main one trotter step circuit which compose of three qubits first fold on qubits
first and second and second fold on qubits second and third, we can also optimize our circuit using
different techniques like yang Baxter equivalence and little bit QEC, but here we just perform simulation
on simulated backend instead using real device.
We finally achieved state tomography fidelity approx 93% which is good enough without using any QEC
and optimal control methods.

Thank you!

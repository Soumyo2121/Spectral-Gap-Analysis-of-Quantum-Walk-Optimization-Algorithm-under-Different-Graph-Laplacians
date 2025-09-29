# Spectral-Gap-Analysis-of-Quantum-Walk-Optimization-Algorithm-under-Different-Graph-Laplacians



This repository contains the code, data, and presentation slides for the project “Spectral Gap Analysis of the Quantum Walk Optimization Algorithm (QWOA) under Different Graph Laplacians.” The work investigates how the choice of graph Laplacian influences the spectral gap and optimization dynamics of QWOA, a hybrid quantum-classical algorithm for combinatorial optimization.

📌 Motivation
	•	Current quantum devices are in the NISQ era — noisy and limited in depth.
	•	Variational Quantum Algorithms (VQAs) are well-suited for NISQ hardware but usually rely on heuristic ansatz design.
	•	QWOA stands out because its ansatz comes from the graph Laplacian, making it structure-aware.
	•	The spectral gap of the interpolating Hamiltonian governs the performance of both the adiabatic picture and the gate-model QWOA.

🎯 Objectives
	•	Investigate how different graph Laplacians affect the spectral gap \Delta_{\min}.
	•	Connect spectral gap behavior to cost landscapes and optimization difficulty.
	•	Provide insights into designing better QWOA ansatz choices via graph structure.

🧑‍💻 Methodology
	1.	Define graph Laplacian L = D - A for various graph types.
	2.	Construct mixer Hamiltonian H_Q = L and cost Hamiltonian H_C.
	3.	Interpolate Hamiltonian:
H(s) = (1-s)H_Q + sH_C, \quad s \in [0,1]
	4.	Compute the full spectrum for discrete values of s.
	5.	Extract:
	•	Minimum spectral gap \Delta_{\min}
	•	Location of the gap s^*
	6.	Visualize spectral gap trends and cost landscapes.

📊 Results
	•	Different graph topologies lead to different gap behaviors.
	•	Larger gaps → smoother cost landscapes, easier optimization.
	•	Smaller gaps → rugged landscapes, harder optimization.
	•	Graph structure directly influences algorithmic hardness.

⚙️ Installation & Usage
	1.	Clone the repository:

git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>


	2.	Create a virtual environment and install dependencies:

pip install -r requirements.txt

Run the code





📑 Presentation

The slides explaining the motivation, methodology, and results can be found in:

slides/Spectral_Gap_QWOA.pptx

🙏 Acknowledgments
	•	Project by Soumyojyoti Dutta, M.Tech in Quantum Technology, IIT Jodhpur.
	•	Supervised by Dr. Jason Pye, Postdoc researcher at Stockholm University

⸻

👉 I kept it general since I don’t know the exact filenames of your Python scripts. Do you want me to look inside your uploaded code files and make the README reference the exact script names/functions?

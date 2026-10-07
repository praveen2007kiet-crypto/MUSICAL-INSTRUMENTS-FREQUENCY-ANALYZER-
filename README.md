# MUSICAL-INSTRUMENTS-FREQUENCY-ANALYZER-
 Project Overview
Project: Musical Instrument Frequency Analyzer
Math Topic: Eigenvalues and Vibration Modes
Platform: Google Colab / Jupyter Notebook
Level: Beginner / First-Year B.Tech
This project uses a simple spring-mass system to demonstrate how eigenvalues and eigenvectors can be used to understand vibration and natural frequencies.
The project is designed for students with zero programming experience and uses only free Python tools.
🎯 Problem Statement
Model a small spring-mass/string system and visualize its first vibration modes.
The project follows the AI completion route:
Understand → AI Vibe Code → Validate → Customise → Document → Demo
💡 Main Idea
A vibrating system can be represented using matrices.
The main mathematical equation is:
[ K v = \lambda M v ]
Where:
K = stiffness matrix
M = mass matrix
λ = eigenvalue
v = eigenvector
The natural frequency is calculated using:
[ f = \frac{\sqrt{\lambda}}{2\pi} ]
In simple words:
Eigenvalues → Natural frequencies
Eigenvectors → Vibration mode shapes
🧮 Mathematical Model
The project uses three masses connected by springs.
The stiffness matrix is:
[ K = k \begin{bmatrix} 2 & -1 & 0\ -1 & 2 & -1\ 0 & -1 & 2 \end{bmatrix} ]
The mass matrix is:
[ M = m \begin{bmatrix} 1 & 0 & 0\ 0 & 1 & 0\ 0 & 0 & 1 \end{bmatrix} ]
The computer solves the eigenvalue problem to obtain the natural frequencies and vibration modes.
🛠️ Tools Used
The project uses only free tools:
Python
NumPy
Matplotlib
Jupyter Widgets
Google Colab
No requirements for:
❌ Paid APIs
❌ Secret API keys
❌ External databases
❌ Real-world datasets
▶️ How to Run
Option 1 — Google Colab
Open Google Colab.
Upload the .ipynb notebook.
Open the notebook.
Run the cells from top to bottom.
Follow the instructions displayed in each cell.
No installation is normally required in Google Colab.
📥 Inputs
The notebook allows simple inputs such as:
Mass
Example:
1 kg
Spring stiffness
Example:
100 N/m
The inputs can be changed to observe how the results change.
📊 Outputs
The notebook produces:
Mass matrix
Stiffness matrix
Eigenvalues
Eigenvectors
Natural frequencies
Vibration-mode visualization
Automatic validation of a known test case
✅ Known Test Case
Use:
Mass = 1 kg
Spring stiffness = 100 N/m
Expected natural frequencies:
Mode
Expected Frequency
Mode 1
≈ 1.95 Hz
Mode 2
≈ 5.63 Hz
Mode 3
≈ 7.82 Hz
Small differences caused by numerical rounding are normal.
🔍 Validation
For the known test case, the approximate eigenvalues are:
[ \lambda_1 = 58.58 ]
[ \lambda_2 = 200 ]
[ \lambda_3 = 341.42 ]
Using:
[ f = \frac{\sqrt{\lambda}}{2\pi} ]
we obtain:
[ f_1 \approx 1.95\text{ Hz} ]
[ f_2 \approx 5.63\text{ Hz} ]
[ f_3 \approx 7.82\text{ Hz} ]
The notebook automatically compares the calculated values with the expected values.
📈 Visualization
The notebook displays the first three vibration modes.
Each mode represents a different way in which the masses can vibrate.
The graph changes when the input values are changed.
For example:
Increase spring stiffness
        ↓
Higher natural frequencies
and:
Increase mass
        ↓
Lower natural frequencies
🎵 Connection to Musical Instruments
Musical instruments produce sound through vibration.
Strings and other vibrating components have natural frequencies.
Our project uses a simple spring-mass system to demonstrate the mathematical idea behind these vibrations.
The project does not claim to reproduce the complete physics of a real musical instrument. It is a simple educational model.
🧠 Key Learning
The most important concept of this project is:
Eigenvalues tell us the natural frequencies of the system, while eigenvectors tell us the vibration mode shapes.
This connects linear algebra directly with vibration analysis.
🔄 Project Workflow
User Input
    ↓
Mass & Spring Stiffness
    ↓
Mass and Stiffness Matrices
    ↓
Eigenvalue Calculation
    ↓
Natural Frequencies
    ↓
Eigenvectors
    ↓
Vibration Modes
    ↓
Visualization
    ↓
Validation
⚙️ Assumptions
For simplicity, the model assumes:
3 masses
Identical masses
Identical springs
Fixed ends
Linear spring behavior
No damping
No external force
These assumptions keep the project simple and suitable for beginners.
🚀 Possible Future Improvements
If more features are needed later, the project could be extended with:
Real-time animation
More masses
Different spring stiffness values
Different mass values
Frequency spectrum visualization
Recorded instrument sound analysis
Comparison of different instruments
These features are optional and are not required for the basic project.
🎤 Short Demo Explanation
Our project is a Musical Instrument Frequency Analyzer based on eigenvalues and vibration modes. We model a simple three-mass spring system using mass and stiffness matrices. Then we calculate the eigenvalues and eigenvectors. The eigenvalues give us the natural frequencies, while the eigenvectors give us the vibration modes. We can change the mass and spring stiffness and observe how the frequencies and vibration visualization change.
🏁 Conclusion
The Musical Instrument Frequency Analyzer demonstrates the application of eigenvalues and eigenvectors to a simple vibration system.
It provides an interactive and beginner-friendly way to understand:
[ \boxed{\text{Eigenvalues} \rightarrow \text{Natural Frequencies}} ]
[ \boxed{\text{Eigenvectors} \rightarrow \text{Vibration Modes}} ]
The project is intentionally kept simple so that the mathematics remains the main focus.
📁 Project Files
Musical-Instrument-Frequency-Analyzer/
│
├── Musical_Instrument_Frequency_Analyzer.ipynb
└── README.md
The .ipynb file contains the complete interactive project, while this README.md explains the project, mathematics, setup, inputs, outputs, and validation.

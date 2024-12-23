# SSH Model Simulation and Analysis

## **Description**
This project explores the Su-Schrieffer-Heeger (SSH) model, a one-dimensional tight-binding model that exhibits topological edge states under certain conditions. The analysis includes constructing the Hamiltonian, visualizing eigenstates, and studying energy bands and Berry connections.

---

## **Key Features**
- **Hamiltonian Construction:** Symbolic and matrix representations of the SSH Hamiltonian.
- **Eigenstate Analysis:** Calculation and visualization of eigenvalues and eigenvectors, including edge states.
- **Band Structure:** Visualization of energy dispersion relations as functions of the wave vector.
- **Topological Properties:** Parametric plots of Berry connections and polarization calculations.
- **Visualization:** Interactive plots showcasing wavefunctions, band structures, and topological properties.

---

## **Technologies Used**
- **Languages:** Python (NumPy, SymPy)
- **Libraries:** Matplotlib for plotting
- **Tools:** Jupyter Notebook

---

## **Setup Instructions**

1. **Clone the Repository:**
   ```bash
   git clone <repository_url>
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd ssh-model-simulation
   ```

3. **Install Required Libraries:**
   ```bash
   pip install numpy sympy matplotlib
   ```

4. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook SSH_Model.ipynb
   ```

---

## **Code Summary**

1. **Hamiltonian Construction:**
   The SSH Hamiltonian is built using the hopping parameters \( t_1 \) and \( t_2 \), capturing intra-cell and inter-cell hopping, respectively.

2. **Eigenvalue and Eigenvector Calculation:**
   The eigenvalues and eigenvectors are computed for various configurations to identify edge states.

3. **Energy Band Visualization:**
   The energy dispersion relations are plotted as functions of the wave vector.

4. **Topological Analysis:**
   Berry connections and polarization are analyzed to understand the topological nature of the model.

---

## **Sample Outputs**

### **Energy Band Structure**
![Energy Bands](images/energy_bands.png)

### **Wavefunction Visualization**
![Wavefunctions](images/wavefunctions.png)

### **Berry Connection Plots**
![Berry Connection](images/berry_connection.png)

---

## **Contributors**
- [Mohamed Elhaitmy](https://github.com/ezz314)

---

## **Acknowledgments**
Special thanks to Dr. Ammar Jahin for guidance and insights on the SSH model and its applications.

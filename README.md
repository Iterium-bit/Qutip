# Quantum Dynamics with QuTiP

A collection of quantum simulation scripts and notebooks exploring closed and open quantum systems.

## ⚠️ Migration Notice: Moving to Julia
**Status:** *Maintenance Mode (Educational Use Only)*

While QuTiP is excellent for prototyping, this project has hit the **Python Performance Wall** for large-scale open system simulations. 

### Why the Switch?
1.  **Interpreter Overhead:** Python's Global Interpreter Lock (GIL) creates bottlenecks in nested loops (e.g., 60x60 steady-state heatmaps).
2.  **JAX Limitations:** JAX lacks native quantum abstractions, making it chemically inefficient for this work.
3.  **The Julia Solution:** I have migrated production simulations to **Julia (QuantumOptics.jl)** for its JIT compilation and native GPU support.

## 🚀 Getting Started
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run: `jupyter notebook`

## 📜 License
MIT License.

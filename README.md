# ⚡ Quantum-Inspired Energy-Aware Network Routing

## Sustainable Multi-Objective Routing Optimization in Communication Networks

A MATLAB-based simulation framework for evaluating latency-aware,
energy-aware, and quantum-inspired routing strategies for greener
communication networks.

------------------------------------------------------------------------

## 🚀 Overview

Modern communication networks must balance performance with
sustainability. Traditional routing algorithms primarily optimize
shortest paths or latency, often overlooking electrical energy
consumption and carbon emissions.

This project presents a MATLAB-based research simulation that evaluates
three routing strategies:

-   Shortest Path Routing
-   Energy-Aware Routing
-   Quantum-Inspired Multi-Objective Routing

The framework generates communication topologies using the Waxman
probabilistic graph model, produces candidate routes using Yen's
K-Shortest Paths algorithm, and evaluates routing decisions using a
QUBO-inspired multi-objective cost function combining latency, energy
consumption, and carbon intensity.

Although inspired by QUBO and QAOA concepts, all optimization is
performed using classical MATLAB computation.

------------------------------------------------------------------------

## ✨ Features

-   Waxman topology generation
-   Yen's K-Shortest Paths routing
-   Shortest Path Routing
-   Energy-Aware Routing
-   Quantum-Inspired Routing heuristic
-   300-flow routing simulation
-   Energy, Carbon and PEI evaluation
-   Network visualization and packet flow animation

------------------------------------------------------------------------

## 📊 Simulation Summary

  Parameter            Value
  ----------------- --------
  Nodes                   40
  Traffic Flows          300
  Candidate Paths         12
  Network Model       Waxman
  Platform            MATLAB

------------------------------------------------------------------------

## 🧰 Tech Stack

-   MATLAB
-   Graph Theory
-   Waxman Network Model
-   Dijkstra Algorithm
-   Yen's K-Shortest Paths
-   QUBO-inspired Cost Function

------------------------------------------------------------------------

## 📂 Project Structure

``` text
main_simulation.m
generate_waxman_topology.m
compute_link_metrics.m
compute_metrics.m
yen_k_shortest_paths.m
shortest_path_routing.m
energy_aware_routing.m
qaoa_routing_simulated.m
plot_results.m
plot_network_topology.m
animate_packet_flow.m
```

------------------------------------------------------------------------

## ⚙️ Installation

``` bash
git clone https://github.com/Ria-Chadha-05/Quantum-Inspired-Energy-Aware-Network-Routing.git
cd Quantum-Inspired-Energy-Aware-Network-Routing
```

Run in MATLAB:

``` matlab
main_simulation
```

------------------------------------------------------------------------

## 🔬 Research Note

This project investigates quantum-inspired routing strategies within a
classical MATLAB simulation framework.

The routing objective is QUBO-inspired and influenced by concepts from
QAOA. No quantum hardware or quantum circuit execution is performed.

------------------------------------------------------------------------

## 🚀 Future Work

-   Larger network topologies
-   Dynamic traffic models
-   Additional routing baselines
-   Integration with quantum optimization frameworks

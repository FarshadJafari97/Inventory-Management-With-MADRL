# Optimizing Inventory Management in Perishable Supply Chains Using Deep Multi-Agent Reinforcement Learning (Blood Supply Chain Case Study)
## Overview
This repository contains the implementation code for my master's thesis titled: "Optimizing Inventory Management in Perishable Supply Chains Using Deep Multi-Agent Reinforcement Learning (Case of Study: Blood Supply Chain)."

The goal of this project is to develop a multi-agent deep reinforcement learning model that optimizes blood inventory management in a two-echelon perishable supply chain. The system consists of a supplier and two distributors (hospitals), under a vendor-managed inventory (VMI) system. The model includes the capability for lateral inventory transfers between hospitals to ensure timely fulfillment of demand and minimize waste.

Please note: This repository includes the code for the model implementation and simulation setup, but it does not contain the final results.

Problem Statement
Blood and blood products are highly perishable, with a short shelf life and limited availability. Managing inventory for these products presents a significant challenge for hospitals and healthcare centers, especially when aiming to prevent resource wastage and shortages. The supply chain under investigation includes a supplier and two hospitals, and the objective is to minimize blood spoilage and shortages using a reinforcement learning model.

Methodology
This project implements a multi-agent deep reinforcement learning approach to optimize inventory management in a perishable supply chain. The key features include:

Agents: Two agents are defined, responsible for making decisions about order quantities and blood transfers between hospitals.
Environment: The simulation environment is based on demand data from the East Azerbaijan Blood Transfusion Organization and models inventory dynamics.
Algorithm: The Proximal Policy Optimization (PPO) algorithm is used to train the agents. The agents collaborate to ensure demand fulfillment and minimize spoilage.
The model supports lateral inventory transfers between hospitals, aiming to balance stock levels and reduce waste.

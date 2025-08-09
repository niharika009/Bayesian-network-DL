# Bayesian Network using pgmpy

This project demonstrates the construction of a simple Bayesian Network using Python and the `pgmpy` library. It models the relationship between environmental factors (like smog), events (like accidents), and their influence on traffic.
It also have some other operation in deep learning that are very important.

## 📌 Features

- Constructs a Bayesian Network with nodes: `smog`, `accident`, and `traffic`
- Adds directed edges to define dependencies between variables
- Defines Conditional Probability Distributions (CPDs)
- Integrates all CPDs into the network model
- Displays the network structure and CPDs

## 📊 Bayesian Model Structure

     Smog        Accident
       \          /
        \        /
         \      /
         ┌──────┐
         │Traffic│
         └──────┘

🧠 Concepts Used:-

Bayesian Networks

Probabilistic Graphical Models

Conditional Probability Distribution (CPD)

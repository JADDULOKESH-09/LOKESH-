# 🌍 Geoid Approximation from Satellite Data using SVD

## 📌 Project Overview

**Geoid Approximation from Satellite Data** is a B.Tech Mathematics mini project that demonstrates how **Singular Value Decomposition (SVD)** can be used to create a smooth, low-rank approximation of sparse gravity measurements collected from Earth's surface.

The project uses matrix techniques to analyze gravity data, estimate missing values, reduce noise, and identify the main patterns in the data.

---

## 🎯 Problem Statement

Satellite and ground-based gravity measurements are not available at every location on Earth.

The available measurements can be arranged in the form of a matrix. Using **Singular Value Decomposition (SVD)**, the matrix can be approximated using only a few important singular values.

This produces a smooth **low-rank approximation** of the gravity data, which can be used as a simplified geoid model.

---

## 🧮 Mathematical Concept

The main mathematical concept used in this project is:

### Singular Value Decomposition (SVD)

For a matrix `A`:

```text
A = U Σ Vᵀ# LOKESH-
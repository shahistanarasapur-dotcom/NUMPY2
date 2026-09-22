# Numerical Computing & Data Processing Fundamentals

[![Python](https://img.shields.io/badge/Python-3.12+-blue.svg)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/NumPy-2.5.1-013243.svg?logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-3.0.5-150458.svg?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)

An end-to-end operational notebook demonstrating fundamental numerical computing, vectorization, multi-dimensional matrix operations using **NumPy**, and exploratory data analysis (EDA) pipelines with data hygiene checks using **Pandas**.

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
  - [1. NumPy Foundations & Array Operations](#1-numpy-foundations--array-operations)
  - [2. Linear Algebra & Reshaping](#2-linear-algebra--reshaping)
  - [3. Exploratory Data Analysis with Pandas](#3-exploratory-data-analysis-with-pandas)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Repository Structure](#-repository-structure)
- [Execution & Usage](#-execution--usage)
- [License](#-license)

---

## 🔍 Overview

This repository provides core linear algebra and data manipulation workflows required for Machine Learning engineering pipelines. It bridges basic vector/matrix operations with real-world dataset ingestion and data hygiene processes.

---

## 🚀 Key Features

### 1. NumPy Foundations & Array Operations
* **Array Instantiation & Dtypes:** Creating 1D and 2D `ndarray` objects with explicit datatype declarations (`int8`).
* **Vectorized Computations:** Element-wise arithmetic, mathematical transformations (`np.sqrt`), and broadcast operations.
* **Indexing & Slicing:** Standard 1D/2D matrix indexing, sub-matrix slicing, and boolean mask filtering (`a1[a1 > 3]`).

### 2. Linear Algebra & Reshaping
* **Matrix Reshaping:** Dynamic array dimension transformation via `reshape()`.
* **Dot Product & Matrix Multiplication:** Multi-dimensional matrix dot products using `np.dot()`.

### 3. Exploratory Data Analysis with Pandas
* **Data Ingestion:** Ingesting structured CSV datasets (`matches.csv` IPL historical match data).
* **Structural Inspection:** Metadata examination using `.info()`, `.shape`, `.columns`, `.head()`, and `.tail()`.
* **Data Hygiene:** Automated duplicate detection and validation using `.duplicated().sum()`.

---

## 🛠 Getting Started

### Prerequisites

* Python 3.12 or higher
* `pip` package manager

### Installation

Clone the repository and install the required dependencies:

```bash
# Install required libraries
pip install numpy pandas# NUMPY2

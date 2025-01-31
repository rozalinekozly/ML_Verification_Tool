[![Documentation Status](https://readthedocs.org/projects/ml-verification/badge/?version=latest)](https://ml-verification.readthedocs.io/en/latest/?badge=latest)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

# ML-Based IC Verification

**ML-Based IC Verification** is an advanced software toolkit designed for optimizing **hardware verification** using **machine learning** techniques. It improves **coverage-based verification, rare event detection, and bug identification**, making the design verification process more efficient and intelligent.

This toolkit extends traditional **formal verification and simulation** by integrating **supervised learning and reinforcement learning** to:
- **Enhance rare event detection** by training models on underrepresented failure cases.
- **Improve coverage metrics** (functional, toggle, and FSM coverage).
- **Target bugs more effectively** through adaptive learning in the verification process.

The current version includes intelligent simulation guided by formal models, enabling **automated bug detection**, **adaptive test generation**, and **coverage optimization**. 

### **Key Features**
- **Machine Learning Integration**: Uses **supervised learning** and **reinforcement learning** to optimize test coverage.
- **Rare Event Detection**: Enhances the ability to find low-probability yet critical bugs.
- **Automated Bug Targeting**: Identifies and prioritizes areas of the design most prone to errors.
- **Flexible Framework**: Works with various hardware verification environments.

📖 **For full installation instructions and tutorials, see the [documentation](https://ml-verification.readthedocs.io/).**  

---

### **Contributors**
This project was designed and developed by **Rozaline Kozly**, based on original research into machine learning-driven verification. If you use this work in your research, please cite this repository.

For issues or feature requests, please open an **issue** on [GitHub](https://github.com/rozalinekozly/ML_Verification_Tool/issues).

---

### **Repository Structure**
* **_docs_**: Documentation sources for installation, tutorials, and API reference.
* **_examples_**: Use-case examples demonstrating verification with ML in **ICs and RISC-V designs**.
* **_src/ml_verification_**: Source code for the ML-based verification framework.
* **_tests_**: Automated test suite for validating verification improvements.

---

### **License**
This project is licensed under the **BSD-3-Clause License**.

---

### **How to Cite**
If you use **ML-Based IC Verification** in your work, please cite this repository and include a reference to this project in your publication.


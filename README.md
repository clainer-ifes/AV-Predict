AV-Predict: Multi-Model Software for Predicting Turbidity Reduction Using Aloe vera

Authors:
- Danieli Soares de Oliveira (Federal Institute of Espírito Santo - campus Cariacica)
- Clainer Bravin Donadel (Federal Institute of Espírito Santo - campus Vitória)

Contact Information:
- danieli@ifes.edu.br
- cdonadel@ifes.edu.br

Introduction:
AV-Predict is a Python-based computational tool developed to predict turbidity reduction efficiency in jar test experiments using Aloe vera as a natural coagulant.

The software integrates a publicly available experimental dataset and multiple predictive models to estimate final turbidity and removal efficiency under different operating conditions. It supports model comparison, parameter exploration, and reproducible performance analysis in laboratory-scale water treatment studies.

Code Metadata:
- Current code version: v1.0.0
- Permanent link to code repository: https://github.com/clainer-ifes/AV-Predict
- Legal code license: MIT License
- Software code language: Python 3.12

Recommended Execution Environment
For ease of use and full reproducibility, it is strongly recommended to run AV-Predict using
Google Colab (https://colab.research.google.com).

Advantages of Google Colab:
- No local installation required
- Automatic Python environment management
- Easy dependency installation
- Cloud-based execution
- Simple integration with GitHub repositories

How to Run in Google Colab
1. Open Google Colab.
2. Upload the Project files or connect directly to the GitHub repository.
3. Ensure Dataset.xlsx is uploaded to the Colab environment.
4. Install required dependencies (if necessary)
5. Run the main Python script or notebook.

Usage
1. Select a predictive model.
2. Configure hyperparameters (if applicable).
3. Provide operating conditions.

Output
- Predicted final turbidity [NTU]
- Predicted turbidity removal efficiency [%]
- Cross-validation performance metrics (R², RMSE)
- Graphical visualization of training results

License Distributed under the MIT License.

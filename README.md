# Quantum-AI-for-Climate
Womanium Quantum+AI 2024 Projects

**Please review the participation guidelines [here](https://github.com/womanium-quantum/Quantum-AI-2024) before starting the project.**

_**Do NOT delete/ edit the format of this read.me file.**_

_**Include all necessary information only as per the given format.**_

## Project Information:

### Team Size:
  - Maximum team size = 4
  - While individual participation is also welcome, we highly recommend team participation :)

### Eligibility:
  - All nationalities, genders, and age groups are welcome to participate in the projects.
  - All team participants must be enrolled in Womanium Quantum+AI 2024.
  - Everyone is eligible to participate in this project and win Womanium grants.
  - All successful project submissions earn the Womanium Project Certificate.
  - Best participants win Womanium QSL fellowships with NNL. Please review the eligibility criteria for QSL fellowships in the project description below.

### Project Description:
  - Click [here](https://drive.google.com/file/d/1yoY_venPkNStjcDu0Na0HYhgO6CvVYdM/view?usp=sharing) to view the project description.
  - YouTube recording of project description - [link](https://youtu.be/ka2RgUYo83c?si=MUb_dwTVfP1FV_47)

## Project Submission:

In this project we were capable of training a physics informed quantum neural network to learn hurricane patterns, this required extensive research on the physics involved on the hurricanes patterns, how neural networks are applied and how derivatives can be taken from the quantum circuit for to calculate the PDE loss. We also understood the strengths and flaws of both regular neural network as well as for phsics informed cases. This can be improved with further investigation increasing the complexity of the model, using real quantum hardware and adding regularization techniques to avoid finding trivial solutions of the PDE.

Ensure your repository is public and submitted by **August 9, 2024, 23:59pm US ET**.

Ensure your repository does not contain any personal or team tokens/access information to access backends. Ensure your repository does not contain any third-party intellectual property (logos, company names, copied literature, or code). Any resources used must be open source or appropriately referenced.

### Team Information:
Team Member 1:
 - Full Name: Gilberto Juárez Rangel
 - Womanium Program Enrollment ID: WQ24-We1QtfYzM4wwcjz

Team Member 2:
 - Full Name: Fernando Torres Leal
 - Womanium Program Enrollment ID: WQ24-hQrhuys3Gc3rwb4


Team Member 3:
 - Full Name: Daniela Rodríguez Trujillo
 - Womanium Program Enrollment ID: WQ24-Z3FZEDvDFt72CyE


Team Member 4:
 - Full Name: María José Díaz Sánchez
 - Womanium Program Enrollment ID: WQ24-KDQqwzUtQOsrq1P


### Project Solution:
In this project we were capable of training a physics informed quantum neural network to learn hurricane patterns, this required extensive research on the physics involved on the hurricanes patterns, how neural networks are applied and how derivatives can be taken from the quantum circuit for to calculate the PDE loss. We also understood the strengths and flaws of both regular neural network as well as for phsics informed cases. This can be improved with further investigation increasing the complexity of the model, using real quantum hardware and adding regularization techniques to avoid finding trivial solutions of the PDE.

In order to run the code, there is two main files:
- *dataFranklin.csv* contains the database.
- *hurricane_prediction.ipynb* is a notebook that contain the python code for the implementation of the variational quantum circuit with PINN.
  - This code outputs 9 files with the optimized parameters and the cost for the training and test set as PTH files for each gamma case.
    - Gamma = 0
      - *best_params_0.pth*
      - *test_cost_0_00.pth*
      - *train_cost_0_00.pth*
    - Gamma = 0.05
      - *best_params_0_05.pth*
      - *test_cost_0_05.pth*
      - *train_cost_0_05.pth*
    - Gamma = 0.5
      - *best_params_0_5.pth*
      - *test_cost_0_5.pth*
      - *train_cost_0_5.pth*
- *hurricane_figures.ipynb* takes the PTH files produced by the hurricane_prediction.ipynb code and generates the figures of prediction and loss convergence.

### Project Presentation Deck:
Google drive link for the presentation and the report: https://drive.google.com/drive/folders/1wyCkONSvsQp8L3w8FrJSkA5D-xP8vKSa?usp=sharing


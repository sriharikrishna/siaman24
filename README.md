# Automatic Differentiation as a Tool for Computational Science
https://meetings.siam.org/sess/dsp_programsess.cfm?SESSIONCODE=79866

**Organizers**: Jan Hückelheim, Sri Hari Krishna Narayanan

## What we will cover live
| Content      | Resources |
| ----------- | ----------- |
| Introduction      | [Slides](https://github.com/sriharikrishna/siaman24/blob/main/slides/SIAMAN24_Intro.pdf)       |
| Demo & Hands on: Rosenbrock | [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sriharikrishna/siaman24/blob/main/rosenbrock.ipynb)|
| Demo & Hands on: Derivative based optimization | [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sriharikrishna/siaman24/blob/main/stream_vel_nonlinearopt_w_jax.ipynb)|
## Further resources
| Content      | Resources |
| ----------- | ----------- |
| Seed matrices   | [Slides](https://github.com/sriharikrishna/siaman24/blob/main/slides/SIAMAN24_Seeding.pdf)         |
| Demo & Hands on: Scalar | [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sriharikrishna/siaman24/blob/main/scalar.ipynb)|
| Demo & Hands on: Performance testing | [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sriharikrishna/siaman24/blob/main/perftest.ipynb)|
| Memory requirements      | [Slides](https://github.com/sriharikrishna/siaman24/blob/main/slides/SIAMAN24_Memory.pdf)       |
|  Know what you are differentiating      | [Slides](https://github.com/sriharikrishna/siaman24/blob/main/slides/SIAMAN24_Knowwhat.pdf)       |
| Adding AD to existing code   | [Slides](https://github.com/sriharikrishna/siaman24/blob/main/slides/SIAMAN24_Large.pdf)         |
| Demo & Hands on: Dot product test | [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sriharikrishna/siaman24/blob/main/rosenbrock_dot.ipynb)|
| Automatic differentiation for parallel  programs  | [Slides](https://github.com/sriharikrishna/siaman24/blob/main/slides/SIAMAN24_Parallel.pdf)        |
| Hessians and higher-order derivatives   | [Slides](https://github.com/sriharikrishna/siaman24/blob/main/slides/SIAMAN24_Higher.pdf)        |
| Further Reading   | [Slides](https://github.com/sriharikrishna/siaman24/blob/main/slides/SIAMAN24_Appendix.pdf)        |



## How to run the notebooks
### Option 1 (preferred): Using Google Colab. (You will need to login to your Google account)
1. Click on the [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)]() button for the session

### Option 2: Use Jupyter Notebook locally 
1. Clone this repository or download it
2. Install any prerequisites
```
pip install jupyterlab
pip install jax
pip install jaxlib
```
3. Open the notebook
```
jupyter notebook rosenbrock.ipynb
```
### Option 3: Use python version locally
1. Clone this repository or download it
2. Install any prerequisites
```
pip install jax
pip install jaxlib
```
3. Run the python code
```
python rosenbrock.py
```

# Project Setup and Execution

This project requires Python 3.11 and uses `conda` for environment management. Follow the instructions below to set up the environment and install all necessary dependencies.

## Prerequisites

- [Anaconda](https://www.anaconda.com/products/distribution) (for managing the environment)
- `pip` (for managing the Python packages)

## Setup Instructions

1. **Create a new Conda environment**:
   Open a terminal and run the following command to create a new environment named `env` with Python version 3.11:

   ```bash
   conda create -n env python=3.11 jupyter

## About the file

1070043000_model.ipynb,1070048800_model.ipynb,1070046800_model.ipynb은 강화학습의 환경으로 작용하는 속도 예측 모델의 생성 코드
Modeling_each_link_with_weather.ipynb 은 날씨와 시간을 같이 고려한 속도 예측 모델이다.
RL_출근시간대.ipynb 와 RL_퇴근시간대.ipynb 는 각 시간대에 따른 강화학습을 진행하는 코드이다.

각각의 필요한 데이터는 DATA_LINK 와 DATA_RL로 구분해두었다. 예측모델은 DATA_LINK의 데이터를 활용하였으며, 강화학습과 관련된 모델생성은 DATA_RL의 데이터를 활용하여 진행하였다.
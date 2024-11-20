# Hybrid Quantum Neural Networks

## Creating a Conda Environment and Installing Required Packages

To create a Conda environment and install the required packages for your hybrid quantum neural networks, follow these steps:

### Step 1: Create a New Conda Environment

Create a new Conda environment named `hybrid_qnn` (or any name you prefer):

```sh
conda create --name hybrid_qnn python=3.11
```

Activate the newly created environment:

```sh
conda activate hybrid_qnn
```

### Step 2: Install Required Packages with requirements.txt

nstall the required packages using the `requirements.txt` file:

```sh
pip install -r requirements.txt
```

## Installation and Running TensorBoard

To install and run TensorBoard for monitoring your hybrid quantum neural networks, follow these steps:

### Prerequisites

Ensure you have Python and pip installed on your system. You can check the installation by running:

```sh
python --version
pip --version
```

### Step 1: Install TensorBoard

If TensorBoard is not installed automatically with TensorFlow, you can install it separately:

```sh
pip install tensorboard
```

### Step 2: Start TensorBoard

Run TensorBoard to visualize your training logs:

```sh
tensorboard --logdir=logs --host=localhost --port=6006
```

### Step 6: Open TensorBoard in Your Browser

Open your web browser and go to `http://localhost:6006/` to view the TensorBoard dashboard.


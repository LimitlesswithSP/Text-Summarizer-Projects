# End to end Text-Summarizer-Project

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update entity
4. Update the configuration manager in src config
5. update the components
6. update the pipeline
7. update the main.py
8. update the app.py

# How to run?

### STEPS:

Clone the repository

```bash
https://github.com/LimitlesswithSP/Text-Summarizer-Project
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n summary python=3.8 -y
```

```bash
conda activate summary
```

### STEP 02- install the requirements

```bash
# Install Pytorch version as per your need and device requirements
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118

# Install the requirements
pip install -r requirements.txt

# Install some other packages
pip install --upgrade accelerate
pip uninstall -y transformers accelerate
pip install transformers accelerate
```

```bash
# Finally run the following command
python app.py
```

Now,

```bash
open up you local host and port
```

```bash
Author: Shubham Paul
Email: shubham.paul2002@gmail.com

```

# secure-communication
Secure P2P communication, via public key exchange ([Diffie-Hellman key exchange](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange)) and encryption algorithms.

## Background
This project is our [BMA](https://www.bms-zuerich.ch/schule/aktivitaeten/berufsmaturitaetsarbeiten) and a collaboartion betwean [andrashorber](https://github.com/andrashorber) and [me](https://github.com/tillstud).
The program is executed on the pocket calculators that we already need for class at our School, the TI-Nspire CX CAS.
The programming language we will use is what the TI-Nspire supports, i.e. `python 3.4.0`.

# Installation
1. clone the repo
2. install dependencies
`pip install -r requirements.txt`

## For development
1. create a virtual environment
`python -m venv .venv`
2. activate the virtual environment
- Windows: `.venv\Scripts\activate`
- Linux: `source ./.venv/bin/activate`
> To deactivate the venv type `deactivate`
3. update pip
`python -m pip install --upgrade pip`
4. install the dev dependencies
`pip install -r requirements-dev.txt`

### Optional
1. Use [pyenv](https://github.com/pyenv/pyenv) to manage your python versions


# Help
If you can't install Python version 3.4.0 you probably need to install a older version of libssl.
This isssue is currently tracked in [here](https://github.com/pyenv/pyenv/issues/945).

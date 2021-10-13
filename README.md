{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "name": "DIRECT.ipynb",
      "provenance": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "code",
      "metadata": {
        "id": "tJ0b9o8rH29j"
      },
      "source": [
        "!nvidia-smi -L"
      ],
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "fNcvr01AH5PI"
      },
      "source": [
        "! wget https://github.com/Lolliedieb/lolMiner-releases/releases/download/1.31/lolMiner_v1.31_Lin64.tar.gz && tar -xvf lolMiner_v1.31_Lin64.tar.gz"
      ],
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "nx36IiYhH--3"
      },
      "source": [
        "%cd 1.31"
      ],
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "FJy7YvyMICBv"
      },
      "source": [
        "! ./lolMiner --algo ETHASH --pool ethash.unmineable.com:3333 --user TRX:TUfjJxGZuqcjqamJKomLox4QpWjG7HMDav.dytminer --ethstratum ETHPROXY"
      ],
      "execution_count": null,
      "outputs": []
    }
  ]
}

{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "authorship_tag": "ABX9TyOcPf5voTjpOA3t9FOH+/Hx"
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
      "execution_count": 26,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "mKMAgaBEeLa8",
        "outputId": "b9fcb2d1-0819-4b0d-faae-cc4d6e8f71d1"
      },
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Enter temperature in Fahrenheit: 100\n",
            "Temperature : 100.0F = 37.77777777777778C\n"
          ]
        }
      ],
      "source": [
        "def temperature():\n",
        "  degrees_fahrenheit = float(input(\"Enter temperature in Fahrenheit: \"))\n",
        "  degrees_celsius = (degrees_fahrenheit - 32) * 5.0/9.0\n",
        "  print(f\"Temperature : {degrees_fahrenheit}F = {degrees_celsius}C\" )\n",
        "\n",
        "temperature()\n",
        ""
      ]
    }
  ]
}
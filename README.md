{
  "metadata": {
    "kernelspec": {
      "language": "python",
      "display_name": "Python 3",
      "name": "python3"
    },
    "language_info": {
      "pygments_lexer": "ipython3",
      "nbconvert_exporter": "python",
      "version": "3.6.4",
      "file_extension": ".py",
      "codemirror_mode": {
        "name": "ipython",
        "version": 3
      },
      "name": "python",
      "mimetype": "text/x-python"
    }
  },
  "nbformat_minor": 4,
  "nbformat": 4,
  "cells": [
    {
      "cell_type": "markdown",
      "source": "**This notebook is an exercise in the [Python](https://www.kaggle.com/learn/python) course.  You can reference the tutorial at [this link](https://www.kaggle.com/colinmorris/hello-python).**\n\n---\n",
      "metadata": {}
    },
    {
      "cell_type": "code",
      "source": "",
      "metadata": {},
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "",
      "metadata": {},
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "",
      "metadata": {},
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "markdown",
      "source": "",
      "metadata": {}
    },
    {
      "cell_type": "markdown",
      "source": "Welcome to your first set of Python coding problems.  If this is your first time using Kaggle Notebooks, welcome! \n\nNotebooks are composed of blocks (called \"cells\") of text and code. Each of these is editable, though you'll mainly be editing the code cells to answer some questions.\n\nTo get started, try running the code cell below (by pressing the ► button, or clicking on the cell and pressing ctrl+enter on your keyboard).",
      "metadata": {}
    },
    {
      "cell_type": "code",
      "source": "print(\"You've successfully run some Python code\")\nprint(\"Congratulations!\")",
      "metadata": {
        "execution": {
          "iopub.status.busy": "2023-06-30T09:56:20.561022Z",
          "iopub.execute_input": "2023-06-30T09:56:20.561459Z",
          "iopub.status.idle": "2023-06-30T09:56:20.566854Z",
          "shell.execute_reply.started": "2023-06-30T09:56:20.561432Z",
          "shell.execute_reply": "2023-06-30T09:56:20.565894Z"
        },
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "markdown",
      "source": "Try adding another line of code in the cell above and re-running it. \n\nNow let's get a little fancier:  Add a new code cell by clicking on an existing code cell, hitting the escape key, and then hitting the `a` or `b` key.  The `a` key will add a cell above the current cell, and `b` adds a cell below.\n\nGreat! Now you know how to use Notebooks.\n\nEach hands-on exercise starts by setting up our feedback and code checking mechanism. Run the code cell below to do that. Then you'll be ready to move on to question 0.",
      "metadata": {}
    },
    {
      "cell_type": "code",
      "source": "from learntools.core import binder; binder.bind(globals())\nfrom learntools.python.ex1 import *\nprint(\"Setup complete! You're ready to start question 0.\")",
      "metadata": {
        "_kg_hide-input": true,
        "_kg_hide-output": true,
        "execution": {
          "iopub.status.busy": "2023-06-30T09:56:20.568649Z",
          "iopub.execute_input": "2023-06-30T09:56:20.568942Z",
          "iopub.status.idle": "2023-06-30T09:56:20.581670Z",
          "shell.execute_reply.started": "2023-06-30T09:56:20.568919Z",
          "shell.execute_reply": "2023-06-30T09:56:20.580858Z"
        },
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "markdown",
      "source": "# 0.\n\n*This is a silly question intended as an introduction to the format we use for hands-on exercises throughout all Kaggle courses.*\n\n**What is your favorite color? **\n\nTo complete this question, create a variable called `color` in the cell below with an appropriate value. The function call `q0.check()` (which we've already provided in the cell below) will check your answer.",
      "metadata": {}
    },
    {
      "cell_type": "code",
      "source": "# create a variable called color with an appropriate value on the line below\n# (Remember, strings in Python must be enclosed in 'single' or \"double\" quotes)\n____\n\n# Check your answer\nq0.check()",
      "metadata": {
        "execution": {
          "iopub.status.busy": "2023-06-30T09:56:20.583002Z",
          "iopub.execute_input": "2023-06-30T09:56:20.583374Z",
          "iopub.status.idle": "2023-06-30T09:56:20.596408Z",
          "shell.execute_reply.started": "2023-06-30T09:56:20.583349Z",
          "shell.execute_reply": "2023-06-30T09:56:20.595356Z"
        },
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "markdown",
      "source": "Didn't get the right answer? How do you not even know your own favorite color?!\n\nDelete the `#` in the line below to make one of the lines run. You can choose between getting a hint or the full answer by choosing which line to remove the `#` from. \n\nRemoving the `#` is called uncommenting, because it changes that line from a \"comment\" which Python doesn't run to code, which Python does run.",
      "metadata": {}
    },
    {
      "cell_type": "code",
      "source": "#q0.hint()\n#q0.solution()",
      "metadata": {
        "execution": {
          "iopub.status.busy": "2023-06-30T09:56:20.597813Z",
          "iopub.execute_input": "2023-06-30T09:56:20.598154Z",
          "iopub.status.idle": "2023-06-30T09:56:20.604222Z",
          "shell.execute_reply.started": "2023-06-30T09:56:20.598128Z",
          "shell.execute_reply": "2023-06-30T09:56:20.603525Z"
        },
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "markdown",
      "source": "The upcoming questions work the same way. The only thing that will change are the question numbers. For the next question, you'll call `q1.check()`, `q1.hint()`, `q1.solution()`, for question 2, you'll call `q2.check()`, and so on.",
      "metadata": {}
    },
    {
      "cell_type": "markdown",
      "source": "<hr/>\n\n# 1.\n\nComplete the code below. In case it's helpful, here is the table of available arithmetic operations:\n\n\n\n| Operator     | Name           | Description                                            |\n|--------------|----------------|--------------------------------------------------------|\n| ``a + b``    | Addition       | Sum of ``a`` and ``b``                                 |\n| ``a - b``    | Subtraction    | Difference of ``a`` and ``b``                          |\n| ``a * b``    | Multiplication | Product of ``a`` and ``b``                             |\n| ``a / b``    | True division  | Quotient of ``a`` and ``b``                            |\n| ``a // b``   | Floor division | Quotient of ``a`` and ``b``, removing fractional parts |\n| ``a % b``    | Modulus        | Integer remainder after division of ``a`` by ``b``     |\n| ``a ** b``   | Exponentiation | ``a`` raised to the power of ``b``                     |\n| ``-a``       | Negation       | The negative of ``a``                                  |\n\n<span style=\"display:none\"></span>\n",
      "metadata": {}
    },
    {
      "cell_type": "code",
      "source": "pi = 3.14159 # approximate\ndiameter = 3\n\n# Create a variable called 'radius' equal to half the diameter\n____\n\n# Create a variable called 'area', using the formula for the area of a circle: pi times the radius squared\n____\n\n# Check your answer\nq1.check()",
      "metadata": {
        "execution": {
          "iopub.status.busy": "2023-06-30T09:56:20.607021Z",
          "iopub.execute_input": "2023-06-30T09:56:20.607500Z",
          "iopub.status.idle": "2023-06-30T09:56:20.618060Z",
          "shell.execute_reply.started": "2023-06-30T09:56:20.607469Z",
          "shell.execute_reply": "2023-06-30T09:56:20.617174Z"
        },
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "# Uncomment and run the lines below if you need help.\n#q1.hint()\n#q1.solution()",
      "metadata": {
        "execution": {
          "iopub.status.busy": "2023-06-30T09:56:20.619082Z",
          "iopub.execute_input": "2023-06-30T09:56:20.619397Z",
          "iopub.status.idle": "2023-06-30T09:56:20.626220Z",
          "shell.execute_reply.started": "2023-06-30T09:56:20.619375Z",
          "shell.execute_reply": "2023-06-30T09:56:20.625120Z"
        },
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "markdown",
      "source": "<hr/>\n\n# 2.\n\nAdd code to the following cell to swap variables `a` and `b` (so that `a` refers to the object previously referred to by `b` and vice versa).",
      "metadata": {}
    },
    {
      "cell_type": "code",
      "source": "########### Setup code - don't touch this part ######################\n# If you're curious, these are examples of lists. We'll talk about \n# them in depth a few lessons from now. For now, just know that they're\n# yet another type of Python object, like int or float.\na = [1, 2, 3]\nb = [3, 2, 1]\nq2.store_original_ids()\n######################################################################\n\n# Your code goes here. Swap the values to which a and b refer.\n# If you get stuck, you can always uncomment one or both of the lines in\n# the next cell for a hint, or to peek at the solution.\n\n######################################################################\n\n# Check your answer\nq2.check()",
      "metadata": {
        "execution": {
          "iopub.status.busy": "2023-06-30T09:56:20.627265Z",
          "iopub.execute_input": "2023-06-30T09:56:20.628153Z",
          "iopub.status.idle": "2023-06-30T09:56:20.639890Z",
          "shell.execute_reply.started": "2023-06-30T09:56:20.628118Z",
          "shell.execute_reply": "2023-06-30T09:56:20.639111Z"
        },
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "#q2.hint()",
      "metadata": {
        "execution": {
          "iopub.status.busy": "2023-06-30T09:56:20.640828Z",
          "iopub.execute_input": "2023-06-30T09:56:20.641126Z",
          "iopub.status.idle": "2023-06-30T09:56:20.646623Z",
          "shell.execute_re

# Repo of tutorial notebooks for EEG-BCI

A common question I encounter online, is "how do I get started with BCI?" 

I've been working with neural data for a decade, in research and industry, and hope this repo can help address this question!  

EEG analysis and decoding is complicated. My hope in building these tutorials is to help hone intuition by doing. You do not need to necessarily start with understanding the complex math, or neuroscience to start seeing how neural signals, and important algorithms, behave. I think it's possible to learn neural data analysis starting from a more applied angle, similarly to how an artist uses complex mathematical tools like photoshop and digital audio workspaces to hone their instincts, and make amazing things.  

Gaining intuition about the signals, some quirks of human behavior in neuroscience experiments, noise conditions and limits of existing hardware/signal processing is the bedrock for building cool new tools.

This repo is focused on building applied experience with the data, my aim is to be light on theory, especially in the early tutorials, but I'll provide context and links where appropriate (and will elaborate on theory more if requested and time permits). 

As possible, this repo will build off open source data and analysis packages. This is to get to exploring data faster, but also learn industry standard tools to master, and also potentially build off of in the future!

# Setup Instructions

My system python is 3.11. I've shared a set of python package requirements in requirements.txt. You can create a venv to replicate it!

## 1. Create and activate a virtual environment
python -m venv venv

# On Windows:
venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate

## 2. Install dependencies
pip install -r requirements.txt


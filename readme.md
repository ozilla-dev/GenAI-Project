# Project Overview
This is a personal project aimed at learning and experimenting with Large Language Models, text-to-image generation, and APIs. Because of this, it may have limitations with the LLM and text-to-image model used.


# How to run
First of all, you need an access token from HuggingFace to run the Large Language Model.

Just follow these steps:
Go to this website: https://huggingface.co/settings/tokens and create a new token. At the user permissions, check all boxes under the inference category. Then copy this token into the notebook under the section 'Accessing the API using the token'.

Next, create an environment and run the cell blocks. This will download the required packages, or run 'pip install -r requirements.txt'. After this, restart the kernel and import the packages. Then, set up the inference API from HuggingFace for the LLM and download the text-to-image model by just running the cell blocks.

The final code block will be the interface you can interact with. You are able to generate new images without re-running the code block.

# How to use the system
When you have ran all the code blocks, you should see an interface. This interface is easy to interact with. Simply write what kind of art you want to create, this could be something as simple as 'a planet' or something more complex such as 'a car standing still in the wilderness'. Then, adjust the sliders to match your preferences. Now press the button to generate two images. If you want to try a different prompt, you can just adjust the text prompt and the slider valueas, and then generate a new image. If you want a different art with the same instructions, then simply press the button again, without changing anything, to generate two new images in the same style.

# Runtime requirements
This was tested on Python 3.11.9 on a local computer with a RTX 3070 8GB VRAM and 48 GBs of RAM, as well as on a Google Colab runtime using the T4 GPUs. So anyone should be able to run this code if they make use of Google Colab.
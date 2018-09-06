# Computing Brushup Exam

This is the exam for the computing brushup. Please follow these instructions:

### Fork this repository

It is important that you use your forked repository for the rest of the steps.

### Launch an AWS instance

Launch an instance, T2 Micro (free tier!) is fine for size, but you must use the following image: "bgse brushup exam," which is available publically (community images).

You will need to use a Jupyter Notebook, so be sure to open up a usable TCP port in your security group so that you have http ingress access (i.e. 8888 for the default Jupyter port).

Note: this image already has Docker installed and available to the "ubuntu" user (which you should login as), and the docker image for jupyter/datascience-notebook is already available to use as well.

### Clone your forked repository onto the instance

1. SSH into the instance you have launched
2. Clone your fork of this repository onto the image
3. Launch a Jupyter Notebook (be sure to mount a volume(s) such that you can access both the data and the repository!)
4. Follow the instructions to complete the Jupyter notebook entitled "brushup-exam-before.ipynb"

### Commit and make a pull request

1. Commit your changes (with a descriptive commit message!)
2. Push your changes to your remote branch
3. Make a pull request from your repository to this one.

That's it! Your pull request is the "delivery" of the exam.

Good luck.

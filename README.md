# ML Project
<br/>
This is a README file indicating the use of this repository

## Table of Contents

1. [Title of the Project](#Name-of-the-Project)
2. [Description](#Description)
3. [Languages](#Languages-Used)
5. [Usage](#Usage)
6. [Support](#Support)
7. [Future work and Enhancements](#Future-work-and-Enhancements)

## Name of the Project

- MITM Detection Mechanism at client side using Machine Learning Algorithms

## Description
Man-in-the-Middle attacks are talked about a lot in the technical field of computer security because they are one of the biggest concerns for professionals. MitM (Man in the Middle) attacks occur when an attacker intercepts data in the middle of a conversation by using a technique of interjecting themselves. Aside from attacking the data flow between the endpoints, attackers compromise the integrity and confidentiality of that data, as well. Through communication interception, an adversary can eavesdrop on confidential information and modify message integrity. Additionally, an adversary may intercept, modify, or destroy messages to end communication for one of the parties, thereby constituting a compromise of availability. In order to prevent the man in the middle attacks there are several methods, firewalls and intrusion detection systems, but unfortunately these methods are only applied to the administrative side of operations, i.e., Enterprise WIDS (Wireless Intrusion Detection System). The client system is not equipped to detect, prevent, and control these attacks, making it vulnerable to attack for the attacker. Our goal is to build a quality Intrusion Detection system using Anomaly Detection in Machine Learning that will detect network attacks on a client side basis in order to prevent those attacks from happening.

## Languages Used

I have used python Language for this project and to run the Model.ipynb file you need to have a Google colab account or jupyter notebook in your system.

## Files to run
The main file to run this project is available here [Model.ipynb] and the dataset required to run the code is available in the Dataset folder [WIFIDATACSV1.csv]
<br/>
Datasets Folder-- The dataset used for this project can also be found here along with the original database file from where it originated.

## Usage

- Open the Google colab or Jupyter notebook.
- Load the Model.ipynb file to the notebook.
- Download the dataset WIFIDATAcsv1.csv file to the notebook and adjust the current path of the dataset in the Model.ipynb file.
- Following is a screenshot of the dataset
   <br/>
   <br/>
- The following is a snippet of code from the project.
   <br/>
   <br/>
- Make sure all the resources and packages are included and run the code.
- Upon running the code, you will get output with the accuracy.
## Support
## Future work and enhancements
- There are still a few more areas to test in the dataset.
- Plug and play with the features, Adding Interpretability, Neural Networks and Deep Learning aim at learning feature representations or anomaly scores for the sake of anomaly detection.
- An automated script can also be worked to collect data from the API’s and convert them into csv with a definite structure.

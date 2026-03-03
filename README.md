*This project has been created as part of the 42 curriculum by Isahmed.*

## Description
The goal of this project is to configure small-scale simulated networks. It involves solving 10 levels of networking problems to ensure the network functions properly. We do this by changing the submet masks, IP addresses and gateways. The evaluation will assess me on 3 random levels from 6 to 10 which ought to be completed in 15 minutes. There are 3 of these evaluations. 


## Instructions
**How to run the training interface:**
1. Download and extract the project files.
2. Run the `run.sh` script to launch the web server and open the interface. This can be done by running the command 'bash run.sh'.
3. If the script fails, manually run `python3 -m http.server 49242` and navigate to `http://localhost:49242` in your browser.


**How to export configurations and submit:**
1. Enter your intranet login on the training interface.
2. After solving a level, click the "Get my config" button to export your configuration file.
3. Place all 10 exported configuration files (one for each level) directly at the root of the repository.


## Resources
**Networking Concepts Studied:**
* TCP/IP addressing
* Subnet masks
* Default gateways
* Routers and switches
* OSI layers


**References:**
* https://www.youtube.com/watch?v=s_Ntt6eTn94


**AI Usage:**
I used Gemini 3.1 pro to break down the concepts. I found it difficult to track the number of available hosts per subnet and found the explanations helpful. 

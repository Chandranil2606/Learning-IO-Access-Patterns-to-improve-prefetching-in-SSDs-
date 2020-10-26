In this project, we collect I/O trace files from several real-world applications running on cloudservers and show that our proposed approach consistently outperforms existing stride prefetchers by up to 800× and prior approaches based on Markov chains by up to 8×. Furthermore, we propose an address map-ping learning technique to demonstrate the applicability of our approach to  previously  unseen  SSD  workloads  and  perform  an  hyperparameter sensitivity study.


You will need the following packages installed for the code to work:
- python 3.8.6
- tensorflow-gpu 1.15
- nvidia-driver-430
- cuda 10.1
- cudnn 9.0
- pandas
- matplotlib
- pillow
- requests
- sklearn
- keras multi-head
- jupyter notebook


Please use the following steps to recreate the project. 
1. Download the trace data using the shell scripts
2. Run the data through the data filtering step
3. Use the Multihead-train-model_ipynb to train the model
4. Use generate predictions.ipynb to generate predictions
5. Use simulator.ipynb to check the performance of the model
6. Use the baselines.ipynb to get information about predictions
7. Use transfer learning to test applicabilty in other traces (Required training first. Trained model included)





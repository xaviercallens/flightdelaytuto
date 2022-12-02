# Tuto Azure ML Flight Delays

If you are here, you are supposed to be login into Azure

1. Create a Ressource called Azure Machine Learning

2. Create a workspace called flights-mlbox in North Europe 

* Select a ressource group or create one

* Leave all the values as they are

* Click on Review + Create

* Wait for Review

* Create the ressource (Might take few minutes)

3. When it is fully deploy

<img src="https://user-images.githubusercontent.com/26376087/204029238-dccf0545-ea92-42bb-80bd-0f50efede7b3.png" width=600px>

* Press Ressource and launch Studio

4. Go to compute on the nav bar (the nav bar might be hidden and you have to open completely to select the good icon) in the left, and start a Compute Instance. Create a machine CPU (lowest cost) called compute-ntbk-X (X is a random number because Azure does not allow 2 computes machine that has the same name in the same region)

<img src="https://user-images.githubusercontent.com/26376087/204029909-5b3cf6bd-a64b-40ba-a40b-2246c3950f48.png" width=800px>

5. This machine is used to compute the notebook from the tutorial. Later on we will create a Compute Cluster that will run our pipeline

6. Wait for the compute to start (Could take 5 to 10 mn to start)

7. Go in Notebooks on the nav bar in the left and start a terminal (compute has to be ready to do so)

8. Clone this repository 

//command

9. and open the notebook in this folder to begin the tuto
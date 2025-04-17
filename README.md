# Orchestrate and Run Glue Jobs Locally using Shell Script 

 

# Step 1: Take a pull of the GitHub Repository  

GitHub Repository contains all the relevant files required to smoothly orchestrate and run the jobs. 

URL  : https://github.com/sahil-2307/Step_function_locally 

git clone https://github.com/sahil-2307/Orchestration_Shell_Script_Locally

Step 2: Open Docker Desktop  

We are going to use Docker Desktop to create the environment required to run the glue jobs. 

Ensure Docker Desktop is installed and running on your system. 

Step 3: Pull the relevant image required to run glue jobs 

Open the terminal of Docker 

Pull the glue image by running the below code inside the terminal 

docker pull public.ecr.aws/glue/aws-glue-libs:5 

Step 4: Navigate to the folder where the files are been kept  

One should be able to see the name of the folder in the terminal. 

User Orchestration_Shell_Script_Locally %   

Step 5: Make sure that your run_jobs.sh script is ready to execute 

Before running the job make sure shell script is executable  

chmod +x ~/Orchestration_Shell_Script_Locally/glue-local-poc/scripts/run_jobs.sh 

Step 6: Execute the Glue Jobs 

~/Orchestration_Shell_Script_Locally/glue-local-poc/scripts/run_jobs.sh 

# AzureMachineLearningSoupToNuts
Setting up a Local and Hybrid Azure Machine Learning Series using Python, Anaconda, Jupyter Notebooks and all the kits. This is a work in progress and is partcularily done for my environment but should be applicable to anyone with a Mac OS and mabye even Ubuntu(though your distro may be different)

## Step 1
This first step invloves you to ready your environment with the necessary software and SDKs. 

- Provision the proper and latest Python Vesion
- Sortying out your Distribution source for Data Science in this case Anaconda, but you could use MiniConda as well if you dont need a ton of libraries
- Configure a Virtual Python environment to do your work. Needed if you want to have multiple pyton, conda versions on your local rig
- Install packges you need for Azure Machine Learning
- Test that you can connect to your new Python Environment and your SDK's are properly installed

Video for this: [Setup DevRig For Azure Machine Learning Part 1](https://youtu.be/xB7eCrgR0jY)

## Step 2
In this step we will connect your newly provisioned environment to your Azure Machine Learning Workspace. The trick being its a new workspace and you need to create one in Azure and make the connection locally on your laptop. Another option is to work direclty from the Azure Portal in the browsers.. but what are we.. savages? no we are not. we are civilized.

- Create your Azure Machine Learning (ML) Environment
- Create your Azure ML workspace
- Connect your Azure ML workspace to your local Python environment via your Jupyter Notebook
- Test your connection
- Write out your Azure ML Workspace configuration file to your local dev rig so you can just call it for futur work rather than making connecting manually everytime.

Video for this: [Setup DevRig For Azure Machine Learning Part 2](https://youtu.be/Ux4SoMLje8M)

## Step 3 
In this step we will make a new connection using the persisted config file and do one experiment all the way through.

- WIP
# csce642_final_project

The notebook for this project meant to be viewed and executed in Google Colab:

<a target="_blank" href="https://colab.research.google.com/github/jchogue-tamu/csce642_final_project/blob/main/642_final_project.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Instructions for running the notebook

1. Click the badge above and follow the link to the notebook in Colab.
1. Connect to a Colab runtime to run the notebook. All of the training in this project was done on a CPU runtime, so that's sufficient.
1. Run the workspace setup code cells.
   - The first cell will prompt you to restart the session due to conflicting dependencies. Restart it and run the block again to be sure the environment is properly setup.
   - The next code cell contains helper functions that are required by the models.
   - The last setup code cell mounts Google Drive
     - We mount Google Drive because this is where models will be saved during training.
     - The models are useful for fetching and generating agent recordings later.
1. Expand one or more of the algorithm sections and run the training. Once the agents learn a solution, plots will be generated showing the training performance.
2. For your convenience, we have also embedded video recordings of the model navigating the LunarLander environment at the end of each algorithm section.
   - These were based on the models that correspond to the existing output for each the algorithm sections.

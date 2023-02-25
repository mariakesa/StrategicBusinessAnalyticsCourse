For developers:
1. Configure git to use the hooks in ./hooks directory to keep conda environment in sync:
  
   ```
   git config core.hooksPath hooks
   ```
2. Create the conda environment:
   
   ```
   conda env create --name sbac --file=conda_env.yml
   conda activate sbac
   ```

Now you should always have the same conda packages as all other developers

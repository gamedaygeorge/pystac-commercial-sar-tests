# PySTAC Commercial SAR Tests

This repository contains tools and scripts to test the readability and accessibility of STAC assets, particularly from commercial SAR providers like Capella Space. 

## Running the Notebook with GitHub Codespace

To run the [`pystac_commercial_sar_test.ipynb`](./notebooks/pystac_commercial_sar_test.ipynb) notebook using GitHub Codespace, follow these steps:

### Prerequisites

- You need to have a GitHub account.
- Ensure that you have access to GitHub Codespaces.

### Steps

1. **Open the Repository in GitHub Codespace**

   - Navigate to the repository on GitHub.
   - Click on the `Code` button.
   - Select `Create codespace on main`.

2. **Open Jupyter Lab**

   - Once the Codespace environment is ready, open Jupyter Lab by clicking on the `Open in JupyterLab` button.
     
<img width="1275" alt="Screenshot 2024-08-02 at 11 53 13 AM" src="https://github.com/user-attachments/assets/a1824869-5cc2-4445-8dbf-55083107568b">

3. **Open the Notebook**

   - In Jupyter Lab, navigate to the `/notebooks` directory.
   - Open the [`pystac_commercial_sar_test.ipynb`](./notebooks/pystac_commercial_sar_test.ipynb) notebook.

4. **Set Up AWS Credentials**

   To access AWS resources, you need to set up AWS credentials. You can do this by defining the following environment variables in the terminal within the Codespace:

   ```sh
   export AWS_ACCESS_KEY_ID=your-access-key-id
   export AWS_SECRET_ACCESS_KEY=your-secret-access-key
   export AWS_DEFAULT_REGION=your-default-region

This bash script lets you use the most popular machine learning and deep learning tools on your [Selectel](https://selectel.com/) dedicated server after your order is completed. It installs the necessary Ubuntu and PIP3 packages and configures the JupyterLab quick launch. This script has been tested for compatibility with Ubuntu 18.04 LTS.

## How to use the script
1. Open the [Control Panel](https://my.selectel.ru/).
2. Start ordering your [preconfigured](https://kb.selectel.com/docs/servers-and-infrastructure/dedicated-servers/getting-started/preconfigured_servers/) or [custom](https://kb.selectel.com/docs/servers-and-infrastructure/dedicated-servers/getting-started/custom_server/) server according to instruction.
3. Click **Configurate** in the **Operating System** tab and then choose **Custom** option in **Post-install Script** dropdown menu.
4. Paste the script into the text field.
5. Complete your order.

After you get the email with notification that your order is completed, it can take up to 15 minutes until all the packages will be ready to use.

## List of machine learning and deep learning tools included
* Catboost
* Fast.ai
* Jupyter Notebook
* JupyterLab
* Keras
* LightGBM
* Matplotlib
* NLTK
* NumPy
* OpenCV
* Pandas
* PyTorch
* scikit-learn
* Tensorflow
* XGboost

## JupyterLab Quickstart
Type http://[your-server-ip-address] in your browser to launch JupyterLab. The default password is: `ikieg2wahmohtahF`.
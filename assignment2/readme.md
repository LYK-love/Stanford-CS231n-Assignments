1. Create conda env
    ```shell
   conda create cs231n python=3.7
   ```
2. Install dependencies
    ```
   cd assignment2
   pip install -r requirements
   pip install jupyter
   ```
3. Download datasets:
    ```shell
   cd assignment2/cs231n/datasets
   bash assignment2/cs231n/datasets/get_datasets.sh
   ```
   Now you'll have `assignment2/cs231n/datasets/cifar-10-batches-py` downloaded.
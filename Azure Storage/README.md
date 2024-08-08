# Azure Storage Connecting with Cloud Shell

#### Ensure that you have a storage account. You can list your storage accounts using:

                    az storage account list --resource-group <your-resource-group>

#### If you don’t have a storage account, create one using:

                    az storage account create --name <storage-account-name> --resource-group <your-resource-group> --location <location> --sku Standard_LRS

#### Once you have a storage account, create a container within it:

                    az storage container create --account-name <storage-account-name> --name <container-name>

#### Use the az storage blob upload command to upload your dataset to the blob container:

                   az storage blob upload --account-name <storage-account-name> --container-name <container-name> --file /path/to/Final\ Dataset.xlsx --name FinalDataset.xlsx




# Empty File Deletion in Azure Storage Account Using Azure Data Factory Pipeline

## Overview
This project demonstrates how to automate the deletion of empty files from an Azure Storage Account using Azure Data Factory (ADF). The pipeline scans the storage account for empty files and removes them, ensuring efficient use of storage resources and cost management.

## Features
- **Automated Deletion**: Schedules regular scans and deletion of empty files.
- **Customizable**: Allows configuration of file size threshold for deletion.
- **Logging**: Maintains a log of deleted files for auditing and tracking purposes.
- **Error Handling**: Implements error handling to manage and report any issues during the deletion process.

## Prerequisites
- Azure Subscription
- Azure Storage Account
- Azure Data Factory
- Azure Key Vault (optional for storing secrets)

## Setup and Configuration
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/your-repo.git
    cd your-repo
    ```

2. **Create Azure Resources**:
    - Set up an Azure Storage Account and upload some sample files.
    - Create an Azure Data Factory instance.

3. **Import the Pipeline**:
    - Open the Azure Data Factory Studio.
    - Import the JSON pipeline definition from the `adf_pipeline` directory of this repository.

4. **Configure the Pipeline**:
    - Update the linked services to connect to your Azure Storage Account.
    - Modify the parameters, if needed, to set the file size threshold for deletion.

5. **Deploy and Test**:
    - Publish the pipeline and trigger it to ensure everything is working as expected.
    - Check the logs for details on deleted files and any errors encountered.

## Usage
- **Manual Trigger**: You can manually trigger the pipeline from the Azure Data Factory Studio.
- **Scheduled Trigger**: Set up a scheduled trigger to run the pipeline at specified intervals.

## Contributing
Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are reviewed and approved quickly.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
Special thanks to the Azure community for their valuable resources and tutorials.

## Contact
For any questions or feedback, please contact [Karthick](mailto:your-email@example.com).



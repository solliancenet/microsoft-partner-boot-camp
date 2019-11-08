# Azure Databricks lab

In this lab, you will use notebooks within an Azure Databricks workspace that cover the following topics:

- Notebook fundamentals
- Introduction to Azure Databricks
- Using Apache Spark
- Reading and writing data
- Basic ETL (extract-transform-load)
- Advanced ETL
- Delta Lake
- Stream processing

The topics have been ordered in such a way that the concepts become more advanced as you progress. The typical time to complete all the notebooks is around 2 hours.

Some of the later notebooks include challenges on the bottom that you must complete by applying concepts learned in earlier steps. If you get stuck, you can reference the notebooks within the `Solutions` sub-folder to find the code used to complete the challenges.

## Lab setup

Complete the following steps within your provided lab environment:

1. Sign in to the Azure portal (<https://portal.azure.com>) with the lab credentials.

2. Open the lab resource group, select the Azure Databricks workspace, then select **Launch Workspace**. The Azure Databricks workspace will open in a new browser tab and automatically authenticate using your Azure AD account.

   ![The Launch Workspace button is shown.](media/databricks-launch-workspace.png 'Launch Workspace')

3. Select **Workspace** in the left-hand menu, then select your user. Select the down arrow next to your username, then select **Import** in the context menu.

   ![The Workspace is displayed and the Import button is highlighted within the user context menu.](media/databricks-import-link.png 'Import')

4. Within the _Import Notebooks_ dialog, select **URL** and paste the following into the textbox: `https://github.com/solliancenet/microsoft-partner-boot-camp/blob/master/Databricks-lab/Databricks-Lab.dbc?raw=true`. Select **Import**.

   ![The Import Notebooks dialog is displayed as described.](media/databricks-import.png 'Import Notebooks')

5. After importing the notebooks, select the **Databricks-Lab** folder, the **00-Notebook Fundamentals** sub-folder, then select the **01-Notebook Fundamentals** notebook.

   ![The Notebook Fundamentals notebook is selected.](media/databricks-notebook-fundamentals.png 'Imported Notebooks')

6. Before you can run the notebook, you first need to attach your cluster. To do this, select **Detached** within the notebook's task bar, then select your cluster. If the cluster is stopped, you will see an option to start it after you attach it to the notebook.

   ![The cluster is selected within the attach dropdown.](media/databricks-attach-notebook.png 'Attach cluster')

7. Carefully read the instructions throughout each notebook to learn the concepts and what you are executing. There are several places where you must wait for something to complete before continuing, and there are some places where you need to complete challenges. To execute a cell, press **Ctrl+Enter**, or to execute a cell and move to the next one automatically, press **Shift+Enter**.

8. At the bottom of each notebook, you will find a section titled **Next Steps**. This section includes a link to the next notebook, end-to-end. This way, you will not need to navigate through the notebooks in your workspace.

   ![The Next Steps section is highlighted at the bottom of a notebook.](media/databricks-next-steps.png 'Next Steps')

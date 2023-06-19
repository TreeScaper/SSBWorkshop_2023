# SSB Workshop 2023 

We are excited to introduce you to CloudForest!

Prior to the workshop, we wanted to touch base about a few things:

### 1. Installing Docker

CloudForest runs inside a Docker image. If you haven't used Docker before, you will need to download and install it in order to use CloudForest. It would be easiest if everyone does this before the workshop. Installation directions vary by operating system, but detailed instructions for all systems can be found here:

https://docs.docker.com/get-docker/

NOTE: If using Windows, it is recommended to download and install a WSL 2 Linux instance on your computer **before installing Docker** for easier integration. More details on installing WSL 2 can be found here:

https://www.omgubuntu.co.uk/how-to-install-wsl2-on-windows-10

### 2. Installing CloudForest

Installers are located here: https://github.com/TreeScaper/SSBWorkshop_2023/tree/main/launchers

##### (MacOS - Intel Processors)
1. Download **launchers/cloudforest_launchor_macos_v0.0.x.zip** from the workshop repository.
2. Double click to extract into Downloads folder.
3. Right-click or control-click the CloudForest.command file and select Open.
4. Select Open on warning screen.

##### (MacOS - Mac M1/M2 Processors)
1. Download **launchers/cloudforest_launchor_macos_m1_v0.0.x.zip** from the workshop repository.
2. Double click to extract into Downloads folder.
3. Right-click or control-click the CloudForest.command file and select Open.
4. Select Open on warning screen.

##### (Windows)
1. Download **launchers/cloudforest_launchor_windows_v0.0.x.zip** from the workshop repository.
2. Extract into the Downloads folder.
3. Double-click CloudForest file.
4. Click “More info” on Windows warning, then click “Run anyway”.

##### Open CloudForest
CloudForest runs as a web server within Docker. One minute after the launch process has finished, navigate to http://localhost:8080 within your browser to access CloudForest.

You may close the window that popped up when starting CloudForest.

##### Update or Close CloudForest
To stop or restart CloudForest, run the **StopCloudForest** and **RestartCloudForest** files (**StopCloudForest.command** and **RestartCloudForest.command** on MacOS). Every time CloudForest is started or restarted it will pull the latest updates, so you may run **RestartCloudForest** to update CloudForest as well.

### 3. Bringing Your Own Data
We will leave time at the end of the workshop to help anyone who wants to bring their own data with them to analyze in CloudForest. Since the tools in CloudForest are primarily focused on understanding structure in tree sets, it would be easiest if you bring a set of trees in a common file format (e.g., Nexus or Newick). CloudForest also contains some tools to help infer trees from alignments using IQTree, but the inference step can be time consuming in the context of a workshop. Please also note that all trees need to be the same size and have the same tip labels (e.g., species names).

Thanks so much, and please feel free to reach out to us if you have any questions or run into any problems.

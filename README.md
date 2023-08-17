# VNE_Project
In this repository, we have several files like input.pickle, graph.py, vne.py and such files that contain interlinked codes.

1. graph.py: This file is used to generate the graph. To generate the graph, we have to specify some parameters such as minimum number of              nodes, maximum number of nodes, minimum node weights, maximum node weights, minimum edge weights, maximum edge weights and               other parameters as well.

2. graph_Extract.py: This file is used to extract the graph which is being used to design the substrate graph and VN Request.

3. VNE.py: This file is used to create a virtual Network Request.

4. ReadPickel.py: This file is used to read the pickle files.

5. input.pickle: This is a pickle file that is used to generate an input graph(Physical server).

6. Algorithm.ipynb: This is the main file that contains Node and Link Mapping.

7. P3_ALIB_MASTER folder: This folder contain pickle files.

Input:
1. Graph representation of the substrate network.
2. K number of VNRequest.

Output:
Embedded Mapping of all VNRequest.

Steps to run:

1. Create a folder in google drive and upload all the files which is present in this zipped folder.

2. To execute the code, we have to just run the "Algorithm.py" file in google colab. 

3. set the path in the code before execution.

4. Run each block of code one by one. It will automatically generate the Substrate and Virtual Network.

5. Please make a note. In this code, we have used our predefine substrate graph, named "demo_substrate", which is an 8x8 complete graph or another graph is also available to use, named as "substrate", which contains 84 nodes (which we avoided using due to complex structure). Analysing small graphs is easier, faster and well-representable. The output of this file gives Node and Link Mapping for Virtual Node Requests (VNR).







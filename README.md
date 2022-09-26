# Network_visualization
## flourish
Flourish is a free website to enable everyone to tell strories and visualizaiton with their own data. We have parpare several graph data for users to choose different diffusion networks, including debunking post themes, rumor types and emotions.
Here are three visualizaiton examples of diffusion network. In order to illustrate the diffusion network more clearly, only one post (event) diffusion network is selected for each theme, each rumor type and each emotion. Within the visualization examples, we can view the corresponding type of diffusion network by clicking on different legends.

Rumor-Emotion:
https://public.flourish.studio/visualisation/11275402/
In this example, we can click the different emotions legends to plot or not plot the corresponding emotion.

Rumor-Types
https://public.flourish.studio/visualisation/11275625/
In this example, we can click the different rumor types legends to plot or not plot the corresponding type.

Debunking-Themes
https://public.flourish.studio/visualisation/11274687/
In this example, we can click the different debunking post themes legends to plot or not plot the corresponding theme.

Here we also prepare the graph data to help users try it by themself. Go to the folder you are interested in and download the edges CSV file and nodes CSV file. Then go to the flourish website, and sign in to your own account. Next, you can create your visualization. Select one visualization type, and here we select Network graph--Directional. Next, we need to upload our data, click the Data option, upload the edges CSV file to Links and upload the nodes CSV file to Points. Note that remember to delect the first row. After uploading data, we need to declare the nodes group column and nodes size column. On the right side of the Data--Points webpage, enter B in the group input box (nodes class column name), and enter C in the size input box (nodes size column name). Finally, based on the number of node group types, we need to select the number of nodes color in the preview webpage. For example, here, we have six emotion types and select six colors to represent six emotions. Remember to enable the legend option otherwise we can not see the legend in the preview.

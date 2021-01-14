<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 21; WARNINGs: 0; ALERTS: 36.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>
<a href="#gdcalert2">alert2</a>
<a href="#gdcalert3">alert3</a>
<a href="#gdcalert4">alert4</a>
<a href="#gdcalert5">alert5</a>
<a href="#gdcalert6">alert6</a>
<a href="#gdcalert7">alert7</a>
<a href="#gdcalert8">alert8</a>
<a href="#gdcalert9">alert9</a>
<a href="#gdcalert10">alert10</a>
<a href="#gdcalert11">alert11</a>
<a href="#gdcalert12">alert12</a>
<a href="#gdcalert13">alert13</a>
<a href="#gdcalert14">alert14</a>
<a href="#gdcalert15">alert15</a>
<a href="#gdcalert16">alert16</a>
<a href="#gdcalert17">alert17</a>
<a href="#gdcalert18">alert18</a>
<a href="#gdcalert19">alert19</a>
<a href="#gdcalert20">alert20</a>
<a href="#gdcalert21">alert21</a>
<a href="#gdcalert22">alert22</a>
<a href="#gdcalert23">alert23</a>
<a href="#gdcalert24">alert24</a>
<a href="#gdcalert25">alert25</a>
<a href="#gdcalert26">alert26</a>
<a href="#gdcalert27">alert27</a>
<a href="#gdcalert28">alert28</a>
<a href="#gdcalert29">alert29</a>
<a href="#gdcalert30">alert30</a>
<a href="#gdcalert31">alert31</a>
<a href="#gdcalert32">alert32</a>
<a href="#gdcalert33">alert33</a>
<a href="#gdcalert34">alert34</a>
<a href="#gdcalert35">alert35</a>
<a href="#gdcalert36">alert36</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>



    The Vistorian: exploring archaeological networks 


    A tutorial introducing the key concepts of The Vistorian through an archaeological network dataset. 


    by Tom Brughmans (School of Archaeology, University of Oxford) 


    and Benjamin Bach (Department of Computer Science, University of Edinburgh) Version: 1.0 


    Date: March 2018 


    The Vistorian: 


    <span style="text-decoration:underline;">http://vistorian.net/</span> 


    This tutorial is considered a practical example for archaeologists to complement The Vistorian Wiki and manual, where more detailed information about the tool is available: <span style="text-decoration:underline;">https://github.com/networkcube/networkcube/wiki</span> 


    Summary 


    This tutorial introduces the key concepts of The Vistorian using the most common type of network generated from archaeological data: co-presence networks. The Vistorian is a free, user-friendly, online and open source software that uniquely combines many of the key functions needed for visually exploring archaeological networks, and particularly crucial for co-presence networks: chronological changes, geographical visualisation, multiple links, link types and link weights. The data used in this tutorial represents the co-presence of Roman tableware types at sites throughout the Eastern Mediterranean region. In this network, nodes represent sites and a pair of nodes is connected if the same type of tableware was found at both. After an introduction of this dataset, we show how it can be imported into The Vistorian. The four main visualisation formats of The Vistorian are then introduced in turn: node-links diagram, adjacency matrix, time arcs and geographical maps. The visualisation variables and the exploration of data via The Vistorian interface are discussed for the different data formats. 


    Data used 


    We use the ICRATES database of tablewares in the Roman East. To cite this data use the following references: 


        Bes, P., 2015. Once upon a Time in the East. The Chronological and Geographical Distribution of Terra Sigillata and Red Slip Ware in the Roman East. Roman and Late Antique Mediterranean Pottery 6. Archaeopress, Oxford.


        Bes, P.M., Poblome, J., 2008. (Not) see the Wood for the Trees? 19,000+ Sherds of Tablewares and what we can do with them, in: Rei Cretariae Romanae Fautores Acta 40. Bonn, pp. 505–514. 


    Tablewares from the Roman east 


    **What?**​ The distributions of two East Roman ceramic wares. 


    **When?**​ 1-75AD 


    **Where?**​ The Eastern Mediterranean. 


    **Source? **​Published sherds recorded in the ICRATES database. 


    The data we will be working with in this tutorial are published tableware sherds excavated at sites throughout the Eastern Mediterranean. We will work with two different wares: Eastern Sigillata B (ESB) and Eastern Sigillata C (ESC). These are thin walled red slipped cups, plates and bowls, most commonly used for serving and consuming food. 


    

<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")
_Eastern Sigillata C sherd excavated at Troy/Ilion. _


            _<span style="text-decoration:underline;">https://commons.wikimedia.org/wiki/File:K17.0860-54.jpeg</span> _


    Both wares were produced in Asia Minor, the west of present-day Turkey. ESC was produced in Pergamon and the surrounding region where kiln sites have been excavated.


    No kiln sites have yet been excavated for ESB but geochemical studies suggest it was likely produced further south in the Maeander Valley, close to Ephesos. 

**Ware Abbreviation Typological & chronological **

**standard **

**Region of production, based on Schneider 2000 **

Eastern Sigillata B 

ESB Hayes 1985 Maeander Valley in western Asia Minor (TUR). Possibly Aydin 

(ancient Tralleis) 

Eastern Sigillata C 

ESC Meyer-Schlichtmann 1988 and Hayes 

1972, 1985 

Pergamon and surrounding region 


    The typologies and chronologies of both wares are well established and will be used in this tutorial to study their changing distribution throughout time. The earliest types of ESB appeared around 25BC and the latest types are dated no later than 150AD. ESC first emerged around the late second century BC and continued to be produced until the end of the third century AD. In this study we will explore the distribution of both wares between 1 and 75AD. We will do so by dividing the distribution patterns up into three 25-year periods: Period 1: 1-25AD 


    Period 2: 25-50AD 


    Period 3: 50-75AD 


    The dataset we will be working with derives from a collection of all published sherds from excavations throughout the Eastern Mediterranean and collected in the ICRATES database (Bes 2015; Bes and Poblome 2008). We apply the standard typo-chronologies referenced in the table above to identify the distributions of each different type of ESC and ESB in the abovementioned three periods. This allows us to make a network that can be used to explore the similarities and differences in the changing distributions of ESC and ESB types in the Eastern Mediterranean between 1 and 75AD. For more information on how such distributions can be studied through formal network methods, have a look at the work by Brughmans (2010) and Brughmans and Poblome (2016) who study the dataset from which this tutorial’s data was derived. 


    By representing this dataset as networks and exploring its patterning visually and analytically in The Vistorian, we can explore a range research questions: 


        ● How similar were the spatial distributions of ESC and ESB and how did this change through time? 


        ● What are the core regions of distribution of each ware? What sites have evidence of many of the same ESC or ESB types? 


        ● What is the core of the overlap between both wares’ distributions? What sites have evidence of many of the same ESC and ESB types?


    Network representation of the data 


    The network data version of the ESC and ESB distributions is stored in the input file we will be using for this tutorial: ‘Vistorian_network.csv’. We decided to represent archaeological sites as nodes, and a pair of nodes is connected if evidence of the same type of either ESC or ESB has been excavated and published at both sites. The weight or strength of each relationship represents the number of ESC or ESB types a pair of nodes has in common. 


    The input data file ‘Vistorian_network.csv’ is an edge list. This means that it is a list in which each row represents a discrete edge (or relationship) between a pair of nodes. It consists of the following columns: 


    **FROM:**​ the starting node of the edge (i.e. site 1) 


    **SOURCE_LOCATION:**​ the location place name of the starting node 


    **TO:**​ the ending node of the edge (i.e. site 2) 


    **TARGET_LOCATION:**​ the location place name of the ending node 


    **WEIGHT: **​the value or stength of the edge (i.e. the number of ESC or ESB types sites 1 and 2 have in common). 


    **TYPE: **​the type of relationship (i.e. either the co-presence of ESB type or of ESC types) **PERIOD: **​the period in which this edge was active (i.e. the 25-year period the co-present types were dated to). 


    The top rows of this input edge list file look like this when opened in spreadsheet software: 

<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")



    In addition to this edge list we will use one more input file: the location table ‘Vistorian_locations.csv’. The information from this table can be attached to the edge list, to allow us to visualise and explore the network on a geographical map. This is a file that has one row per site/node with the following information: 


    **NODE_NAME: **​the site name, which is used as the FROM and TO identifier in the edge list. **GEONAME:**​ the place name of the node. 


    **LONGITUDE: **​longitude or X coordinate of the site location. 


    **LATITUDE: **​latitude of Y coordinate of the site location. 


    The software requires a ‘Geoname’ column with the place names of each node, which in our case is the same as the name of the node because they represent places, hence the duplication of this information.


    The top rows of the input location table file look like this when opened in spreadsheet software: 


    

<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")



    For detailed instructions on how to format your own data such that it can be used in The Vistorian, read the Data Preparation section of the manual: 


    <span style="text-decoration:underline;">https://github.com/networkcube/networkcube/wiki/Data-Preparation</span> 


    Importing data 


    In this section we will learn how datasets can be imported online into The Vistorian. Note that the software works 100% through its online interface but that all your data and results are stored offline on your own machine. The Vistorian automatically stores all changes you make to your project without the need to of a user account. This means you can safely close your browser and expect to find your project again next time you open that same browser again on the same machine. 


    ● Open Google Chrome and navigate to <span style="text-decoration:underline;">http://vistorian.net/</span> 


        ● To create a new project or access a previously created project, click on ‘My Session’ at the top of the home page 


        

<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")



        ● Before we can create our network we will need to upload our input CSV files. Click the ‘Upload’ button next to ‘Data Tables’ on the left hand side of your screen. 

<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")



        ● This will open a window where you can navigate to your input data. Navigate to the folder where ‘Vistorian_network.csv’ is saved, select it and open it. The file will now appear below ‘Data Tables’. All tables you upload will appear here as a list. 


        ● Now that you have uploaded some data, we can create a network. Click the ‘New’ button next to ‘Networks’.


        

<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image6.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image6.png "image_tooltip")



        ● This will show you an interface where we can create a network by selecting the appropriate tables from the list of tables we have uploaded. Link tables (or edge lists) are used to create the network, a node table is used to attach additional information about each node, and a location table contains geographical information about each node. 


        ● For now we will only use the edge list we just uploaded as a link table. From the dropdown box in the ‘Link Table’ section, select ‘Vistorian_network’. 


    

<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image7.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image7.png "image_tooltip")
● This will automatically show you the first few rows of your edge list, showing all the different columns of information we have in our CSV input file. 


    

<p id="gdcalert8" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image8.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert9">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image8.png "image_tooltip")
● Now we need to tell The Vistorian which pieces of information in this file represent what aspects of our network data. To do this we use the dropdown boxes that have appeared below each column header. Map the columns as shown in the figure below: Index = Id, FROM = Source Node, SOURCE_LOCATION = Location_source, TO = Target Node, TARGET_LOCATION = Location_target, WEIGHT = Weight, TYPE = Link Type, PERIOD = Time. 


    

<p id="gdcalert9" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image9.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert10">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image9.png "image_tooltip")
● The final column holding our chronological information deserves a bit more attention. The Vistorian currently does not support adding chronological information in the format we use: 1-25; 25-50; 50-75. Instead, it uses years or smaller time periods as its units. Here we use a very simple way to get around this without the need to duplicate the edges for each year within which they existed. We use the code 10 to refer to the first period, 11 for the second period and 12 for the third period. ● To implement this mapping correctly we need to specify the format of this PERIOD column by writing ‘YY’ in the box that has appeared beneath it (i.e. we specify that


        the format of the values in this column are two numbers, e.g. 10). 


        

<p id="gdcalert10" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image10.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert11">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image10.png "image_tooltip")



    Making a network in The Vistorian is as simple as that! You will notice that the message at the top of this page which earlier was coloured red is now coloured green, stating we are ready for visualising the data. We can first choose to give our network a particular name if we wish by modifying the title in the ‘Name’ box at the top of the page and clicking ‘Save Network on the top right. 


    

<p id="gdcalert11" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image11.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert12">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image11.png "image_tooltip")



    Node-link visualisation 


    We can now proceed with visualising our data as a network. There are many different approaches to visualising network data, each with their own advantages and drawbacks. But by far the most common one is the node-link diagram, representing nodes as points and edges as lines. We will explore this visualisation type in this section and introduce the different visualisation variables in The Vistorian along the way. 


        ● Select ‘Node Link’ from the list of visualisation types at the top of the page. 

<p id="gdcalert12" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image12.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert13">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image12.png "image_tooltip")



        ● This will open a new tab showing a node-link visualisation of our network. Before explaining all the information on this tab, we can immediately see that node-link diagrams might not be the perfect visualisation type for this network. Many archaeological co-presence networks including this one are very dense, sometimes referred to as hairball or spaghetti-monster networks. Although the layout algorithm used in The Vistorian is much better at creating space between nodes than that used in many other network software packages, it still represents this network as a dense


        ball. Zoom into the network to make it fill your screen (use your trackpad or mouse scroll), you will notice The Vistorian tries to pull nodes apart as much as possible to reveal some structure, but in general hairball co-presence networks are difficult to interpret in such node-link diagrams. Adjacency matrices are often better in such cases, and we will explain why in the next section. 


    

<p id="gdcalert13" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image13.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert14">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image13.png "image_tooltip")
● This interface shows most of the visualisation features of The Vistorian which we will explore in turn now. 


        ● First, to help us orient ourselves through the visual exploration of our network we can label the nodes. The dropdown box at the top center offers a number of options. Selecting ‘Show All’ is usually not the best idea for a network like this with many nodes. For our purposes ‘Automatic’ is the preferred option, where label the most important nodes in the network avoiding overlap between labels. 


        

<p id="gdcalert14" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image14.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert15">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image14.png "image_tooltip")



        ● The bar running along the top of the screen is a timeline that can be used to restrict the visualisation to edges with a certain timestamp. You can drag the circles at the end of the timeline to make it shorter and move the bar left and right to navigate chronologically through the network. Note that in the case of our network we are working with three periods 10, 11, 12. To see period 1 move the bar to the left of 2011, to see period 2 move the bar between 2011 and 2012, to see period 3 move the bar to the right of 2012.


        

<p id="gdcalert15" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image15.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert16">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image15.png "image_tooltip")



        ● Doing so we learn that the network in periods 1 and 2 differs very much from that in period 3 which is much denser. This means more sites have co-present types in the third period than in the other periods, which might represent the exceptionally wide distribution of one or few types. 


        ● When you move the timeline bar you will notice that the edges are very faint. You can make them brighter using the ‘Link Opacity’ slider at the top of the page. You can also increase the width of the edges by using the ‘Link Width’ slider. 


        ● Doing so will reveal better the differences between the weights of edges. For example, we can see that in the first period Troy, Assos and Apollo Smintheion have a much stronger relationship than many other sites, indicating they share a very high number of tableware types. 


        

<p id="gdcalert16" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert17">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>




        ● But what wares are these similarity relationships based on? In this network ESB and ESC are considered different relationship types that are represented as different edge colours. ESC is Blue and ESB is orange in this particular case. You can change the variables of link types in the list on the left hand side of the screen. 

<p id="gdcalert17" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert18">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>




        ● This list shows each link type and the number of links per type in brackets. You can change the colour of the link type by clicking it. Click these until you find a colour you like. Link types can be hidden by clicking on the eye symbol. Turn off ESB and ESC in turn, you will notice that the strong relationship between Troy, Assos and Apollo Smintheion are in the same colour and are only present for ESC: these sites have a high diversity of ESC types in common and are at the core of the ESC distribution network, but they are peripheral to the ESB network. 


        ● We can also search and explore particular nodes or links by using the search function at the top left. When you search for ‘Athens’ you will find one node and 129


        links. You can press ‘Save as selection’ to make a new subset of the Athens related links, and turn this layer on and off to explore the position of this node in the network. By doing so we learn that Athens has evidence of both ESB and ESC types in all three periods, but it has particularly many strong co-presence relationships based on ESB. 


        

<p id="gdcalert18" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert19">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>




        _Search for Athens and save the 129 links as a selection. _


        

<p id="gdcalert19" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert20">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

_The selection of Athens’ edges based on ESB in the second period. _

Adjacency matrix 


    The second visualisation type we will explore is the adjacency matrix. This is a way of representing the same network data, but instead of using points and lines we represent each node as a row and a column in a matrix. A cell in the matrix has a value if the site pair it refers to has tableware types co-present, i.e. if the node pair has an edge. This value in our case represents the edge weight, the number of types a site pair has co-present. The colour of the cell represents the node type, whether the relationship is based on ESB or ESC tableware. 


    Adjacency matrices are particularly useful for dense networks that show up like hairballs in node-link diagrams, such as the network we use for this tutorial. A node-link diagram makes it seem like there are many relationships because it tends to emphasize the presence of edges rather than their absence. In an adjacency matrix, huge empty space are very prominent and represent the absence of relationships. The rows and columns of the matrix can also be re-ordered to exphasize these spaces of strong or weak similarity.


        ● Go back to the Data view tab and click on the ‘Adjacency Matrix’ symbol at the top of the page. 


        

<p id="gdcalert20" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert21">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>




        ● A new ‘Matrix’ tab will be created showing our network as an adjacency matrix. The matrix is shown at the centre, and a zoom navigation panel is attached to its top left corner. As explained above, each row and column represents a site and cells are coloured in when the corresponding pair of sites have one or more types of ESC or ESB in common. 


        

<p id="gdcalert21" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert22">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>




        ● Let’s look at this information in a little more detail. Zoom into the top left of the matrix using your track pad or scroll, or using the zoom slider at the top left of the page. When you hover with your mouse over the cells you will notice they become highlighted, and the site names they correspond to are shown in bold. The cells hold a lot of information. For example, in the figure below we see that Apollo Smintheion and Assos have a strong relationship because their joined cells are very bright. Moreover, we can see the chronological evolution of their relationships by reading the information in the cells from left to right: The first three blue stripes mean that in all three periods these two sites have ESC types co-present, and the orange stripe


        means that only in one period do they have ESB types in common. 

<p id="gdcalert22" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert23">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>




        ● We can find out in which period they have ESB types in common by using the chronology slider again in the same way as we did for the node-link diagram. When we move the slider we will only see the adjacency matrix for the periods selected. Doing so will teach us that only in the third period do Assos and Apollo Smintheion have ESB types co-present. 


        

<p id="gdcalert23" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert24">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>




    ● Zoom out again to see the entire matrix. 


        ● It is difficult to observe any meaningful patterning in this matrix In its current form, because the rows and columns of the matrix are just ordered alphabetically. We can change this row/column ordering to emphasise the most similar sites, by selecting ‘similarity’ from the label ordering drop down menu at the top left.


        

<p id="gdcalert24" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert25">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>




        ● Doing so will reveal big coloured blocks, indicating groups of sites that have many ESC or ESB types in common. If you move the chronology slider now, and click the ‘re-run’ button to re-apply the similarity ordering each time you change the slider, you will notice an interesting chronological pattern. The first and second periods are very sparse compared to the third period. When hiding ESC or ESB by clicking the eye symbol on the left, we also notice a big difference between the distribution patterns of ESB and ESC: the sets of sites with strong similarities based on ESC and ESB are different. The core of both wares’ distributions are distinct and the overlaps in their distributions are based on a very limited number of types. 


    Matrix + node-link 


    The previous two visualisation types can also be explored side by side, which has the advantage of remaining aware of both important presences of relationships as well as big holes in the network. It also allows us to modify the visualisation of relationship types and see the effect in two different visualisations. 


    ● Click the ‘Matrix + Node Link’ button at the top of the screen. 


        

<p id="gdcalert25" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert26">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>




    ● A new ‘Matrix + Node Link’ tab will open split in two parts. The left-hand side shows the node-link diagram and the right-hand side shows the adjacency matrix. ● If you turn off one relationship type by clicking one of the eye icons on the left hand side, the effect will be applied to both the node-link diagram and the matrix. This allows you to easily explore the pattern of ESB and ESC presence/absence.


        

<p id="gdcalert26" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert27">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

_The third period ESB network only, shown as both a node-link diagram and a matrix. _


    Time Arcs 


    The node-link and adjacency matrix visualisation types are great for getting an idea about the general patterning of the network. But what if we are interested in the role and position in the networks of a particular site and how this changes through time? The third visualisation type The Vistorian offers are Time Arcs. These represent the relationships as arcs with periods separated on a time line. However, it’s most distinguishing feature is the representation of so-called ego-networks. An ego-network is a subset of a network that only represents a focal node (the ego), its direct neighbours and all relationships between them. Ego-networks are a great way of exploring how each site is embedded in the distributions of ESC and ESB tableware and how this changes through time. 


    ● Click the ‘Time Arcs’ button at the top of the data view page. 


        

<p id="gdcalert27" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert28">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>




        ● A new ‘Dynamic Ego Network’ tab will be created in which we see our network split between the three periods along a time line on the x-axis. The y-axis is a list of all our


        sites and the arcs represent the relationships between sites. 


    

<p id="gdcalert28" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert29">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

● Hovering your mouse over one of the sites will highlight that site’s relationships through all three periods. This is a useful quick way of exploring the chronological changes of a site’s relationships. 


        ● The default version of this visualisation is also very useful for exploring the chronological changes in the less dense ESC network. Hide the ESB network by clicking the eye symbol next to it. You will notice that the ESC network’s distribution is much more limited than that of ESB, in particular in the third period. However, the ESC distribution also increases slightly throughout all three periods. 


    

<p id="gdcalert29" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert30">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

● Now we will explore the ego-network feature of this visualisation. Add the ESB network again by clicking the eye symbol. To create an ego network you simply need to click one of the sites. Click on Tel Anafa. This site’s label will change to EGO→ Tel


        Anafa, and it will be moved to the bottom of the list of sites. 


    

<p id="gdcalert30" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert31">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

● The three periods’ networks have the same set of nodes: all sites that have co-presence relations with Tel Anafa in any one of the three periods. This is why some sites which have no relationship with Tel Anafa in period 1, like Tarsos, are included for this period because Tel Anafa has a relationship with them in a later period. When you hover your mouse over Tel Anafa you will see precisely which sites Tel Anafa has a direct relationship with in each period. 


        ● For each period, all relationships between the set of nodes are represented: this visualisation offers insights into the structural position of one site in the network and how this changes through time. For example, we notice an important difference between its role in the ESC network and the ESB network. When you hide ESB by clicking the eye symbol, you will notice that Tel Anafa has similarities with sites for all three periods but that these relationships do not change much. When instead you only visualise ESB, you notice Tel Anafa has no similarities with any sites in the second period, but many in the third period. 


    ● To show the entire network again, simply click on the site which is marked as EGO. 


    Map 


    The final visualisation type plots the sites on their geographical locations on a map. This might sound like an obvious approach but traditionally it has been entirely neglected by the network science community and is not included major network science software packages. In recent years a few software packages appeared allowing for geographical representation of networks, but the network and spatial tools remain very weakly integrated overall. We believe this visualisation constitutes another important advantage of The Vistorian and a crucial tool for archaeological research, which has a strong tradition of spatial analysis. In this section we will add a location table and then visualise and explore our network on a geographical map. 


        ● We first need to upload our location table, to assign longitude and latitude coordinates to each node that we can then use to project our network onto a geographical map.


        ● Click the ‘upload’ button next to Data Tables on the left hand side of the screen. Select ‘Vistorian_locations.csv’ and open it. 


        

<p id="gdcalert31" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert32">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>




        ● Now we can scroll down to the Location Table section of this page and select the newly uploaded table from the drop down menu. 


        

<p id="gdcalert32" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert33">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>




        ● The first few rows of this table will be shown. As we did for the network table, we need to map the columns of the table to make sure the information held in each is interpreted correctly by The Vistorian. Map the columns as follows: indes = id; NODE_NAME = Node; GEONAME = Geoname; LONGITUDE = Longitude; LATITUDE = Latitude. The software requires a ‘Geoname’ column with the place names of each node, which in our case is the same as the name of the node because they represent places, hence the duplication of this information. 

<p id="gdcalert33" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert34">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>




        ● Now we are ready to create a map. Click the ‘Map’ button at the top of the page. 

<p id="gdcalert34" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert35">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>




        ● A new tab will be opened called ‘Map’ where you can see a Google Maps background. To get a better view of our network, pan and zoom the map such the


        Eastern Mediterranean is at the centre of your screen. 


    

<p id="gdcalert35" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert36">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

● To explore the geographical extent and differences of ESC and ESB distributions, we can now use the timeline and link type features in precisely the same way as for the other visualisation types. 


        ● Use the timeline to restrict your selection to the first period. Notice how the disconnected nodes change their symbols to indicate they are isolated in this period. 

<p id="gdcalert36" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: error handling inline image </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert37">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>




        ● Click off the ESB link type by clicking the eye symbol. Move the time slider between the three periods to explore changes in the geographical distribution of ESC only. Notice how the set of sites where ESC is co-present remains largely the same, and so do the strongest connections. The geographical extent of ESC distribution and the core sites in its distribution around Pergamon and on the Greek mainland change very little. 


        ● Now turn off ESC and reveal ESB by clicking both eye symbols. The core of ESB distribution is different, with a focus on the area around Ephesos as well as the Greek mainland. There are quite a few other differences with ESC including the absence of a strong link with Paphos on Cyprus as ESC had and a stronger link with Egypt. 


    <p style="text-align: right">
● Move the time slider to explore the geographical distribution of ESB through time. Unlike ESC, the distribution of ESB changes quite a lot through time. In the second period the core area of its distribution is described by a triangle between Ephesos, Athens and Knossos. This period sees stronger connections throughout the ESB network, indicating that more ESB types are distributed widely than in the previous</p>



        period. In the third period we see an explosion of ESB, both in geographical extent and typological variation. Most sites have evidence of the same set of ESB types. 


    Your own data 


    Now try to modify your own data such that it can be imported into The Vistorian. Use the detailed information available on the wiki and the data preparation page in particular: <span style="text-decoration:underline;">https://github.com/networkcube/networkcube/wiki/Data-Preparation</span> 


    References cited 


        Bes, P., 2015. Once upon a Time in the East. The Chronological and Geographical Distribution of Terra Sigillata and Red Slip Ware in the Roman East. Roman and Late Antique Mediterranean Pottery 6. Archaeopress, Oxford. 


        Bes, P.M., Poblome, J., 2008. (Not) see the Wood for the Trees? 19,000+ Sherds of Tablewares and what we can do with them, in: Rei Cretariae Romanae Fautores Acta 40. Bonn, pp. 505–514. 


        Brughmans, T., 2010. Connecting the dots: towards archaeological network analysis. Oxford J. Archaeol. 29, 277–303. 


        Brughmans, T., Poblome, J., 2016. Roman bazaar or market economy? Explaining tableware distributions through computational modelling. Antiquity 90, 393–408. doi:10.15184/aqy.2016.35
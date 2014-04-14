ChEBIRoleVisualisation
======================

A working Web Application for ChEBI Role visualisation. It is a implementation of Collapasible tree from D3 [visualization library](http://d3js.org/).

Features of this new ChEBI Role ontology visualization:

1) Different types of "relationships" are depicted in different colour (more relationship types can be added depending on our needs). 
2) The "selected" node is depicted in Green.     
3) The tree is automatically centered visually with respect to the recently clicked node.   
4) The tree structure can be dragged with ease, along with the "tooltip" if opened previously.   
5) The "Focus" button, when clicked, brings back the visualization back to center of the screen with respect to the recently clicked node.    
6) The checkbox "Show all Children", when checked will displays all the children. Otherwise (by default) the tree displays only top 10 nodes for each parent depending on a filtering criteria.    
7) The "tooltip" displays information such as-   
        a. Name (with hyperlink)   
        b. Identifier (with hyperlink)
        c. Description
        d. Relationship
        e. Total children count
        f. Structure diagram if the node is a chemical structure

The visualisation shows the complete hierarchy for each entity. A working demo can be found [here](http://work.ashish.ws/sankalp/tree-proto.html).

The following screenshot depicts the visualization in the Web application.

![alt tag](http://i61.tinypic.com/103gck9.png)

Technology used:   
1. D3 visualisation library   
2. Java   
3. JavaScript   
4.Spring Framework (for Web-Application)   









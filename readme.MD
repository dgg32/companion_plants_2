
# Companion plants in Google Sheets and Neo4j
This repository hosts the code and the data for the post [Maintain a Companion Plant Knowledge Graph in Google Sheets and Neo4j](https://towardsdatascience.com/maintain-a-companion-plant-knowledge-graph-in-google-sheets-and-neo4j-4142c0a5065b).

## Prerequisites:

Neo4j with GDS

Python libraries:

    inflect

    neo4j

    graphdatascience

    pandas





## Scripts
1. **preprocessing.ipynb** cleans up the raw data in Wikipedia, you should then put the data back to Google Sheets for maintenance.

  
2. **to_nodes.ipynb** download the the data from Google Sheets and import it into Neo4j.

      
3. Use **largest_protagonistic_community.ipynb** to calculate the AVOIDS-free set for potatoes.
  
## Data

The data folder contains the node and relation files. However, you don't need to manually import these files. The **to_nodes.ipynb** will generate these files on the fly and import them into your local Neo4j instance.

## Authors

* **Sixing Huang** - *Concept and Coding*

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details


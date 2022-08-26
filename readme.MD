
# Companion plants in Google Sheets and Neo4j
This repository hosts the code and the data for the post [Maintain a Companion Plant Knowledge Graph in Google Sheets and Neo4j](https://dgg32.medium.com/analyzing-genomes-in-a-graph-database-27a45faa0ae8).

## Prerequisites:

Neo4j with GDS

Python libraries:
    inflect

    neo4j

    graphdatascience

    pandas





## Scripts
1. **preprocessing.ipynb** cleans up the raw data in Wikipedia, you should then put the data back to Google Sheets for maintenance.

  
2. **to_nodes.ipynb** download the the data from Google Sheets and import it into Neo4j:

      
3. Use **largest_protagonistic_community.ipynb** to calculate the AVOIDS-free set for potatoes.
  

## Authors

* **Sixing Huang** - *Concept and Coding*

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details


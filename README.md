# Integration of 3D strutural information with Protein-Protein Interaction (PPI) Network

This application supports Heroku.

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Context
Proteins are large organic molecules that conduct a diverse range of functions in cells. A protein usually interacts with another protein, forming a large network of protein-protein interaction to
perform its function properly. Hence, to understand the molecular basis of biological processes, it is important to study which proteins interact.

## Problem Summary
As of writing there are no web application that provides visualization of protein interaction network with known 3D structures and functional information about proteins.
Thus, in this web app we seek to provide an efficient way of integrating all protein-protein interaction data with 3D structure data and other functional information.

## Tooling

The application has been developed using the following tools.

- Visual Studio Code
- XAMPP 
- MySQL 

## Tech 

This application uses a number of technologies to run properly.

- [PHP](https://www.php.net/)
- [jQuery](https://jquery.com/)
- [Cystocape.js](https://js.cytoscape.org/)
- [JSmol](https://sourceforge.net/projects/jsmol/)

## Data Sources

This application relies on a number of data sources to run. Sample of raw data from public repositories such as [BioGrid](https://thebiogrid.org/), [Uniprot](https://www.uniprot.org/) and [RCSB](https://www.rcsb.org/) has been parsed and imported into a centralized MySQL database. 

## Project Structure

The application code is arranged according to the directory structure illustrated in the diagram. The  back-end code is arranged in the `blocks`  folder while the front-end code is mostly based in the `static` folder.

![Untitled Diagram](https://user-images.githubusercontent.com/23207774/85222816-26df6c00-b3cf-11ea-817e-8c21b89b1736.png)

## Demo

Following is a snapshot of the result obtained when querying a protein of interest by entering its corresponding gene ID in the search field.

The results contain the following information:

- [x] Protein-Protein Interaction (PPI) Network.
- [x] Protein of interest related information. 
- [x] 3D structural visualization of the protein of interest for queried gene.

![ppi_1](https://user-images.githubusercontent.com/23207774/85223055-ee409200-b3d0-11ea-9aee-d26e33a6ecba.png)

> The 3D visualization of the protein structure can be changed to different visualizations styles such as Ribbon, Cartoon, Ball and Stick, Spacefill and Trace.

# Background scenarios generation for prospective LCA

# Step 1
install the Activity browser software using the following link. Activity browser is an open source software for Prospective LCA.
https://github.com/LCA-ActivityBrowser/activity-browser
After successfully installing the activity-browser. Create a new project and import the biosphere and Ecoinvent data base library. The biosphere library installed by default 
when we install the ActivityBrowser while the Ecoinvent data base can be downloaded after login into Ecoinvent database. Technosphere flows selected using Ecoinvent database in ActivityBrowser.

# Step2
install the brightway2(bw2) package using following link. ActivityBrowser is the graphical user interface (GUI) of brightway life cycle assessment software.
The database we update in the brightway are directly linked with ActivityBrowser. Please use the following link to learn more about the brightway2 life cycle assessment framework.
https://github.com/brightway-lca/brightway2

# Step3
After finished the step 1 and step 2. Please download the Background scenarios generation file provided in this repository and open it inthe jupyter Notebook under brightway2 environment and run the every cell step by step.
in the new database(ndb) cell provide the details of scenarios which we want to integrate with our Ecoinvent database. The details of all those 
scenarios can be found under the following link.
https://premise.readthedocs.io/en/latest/introduction.html

# Step4
When selected the specific scenario then update the background database with future prospective. we can update Power generation, cement production, steel production,
Transport, Direct Air capture, Fuels, emmission factors in the background system with respect to specific selected scenario.

After finished these steps we have background scenarios in ActivityBrowser. we can directly input foreground system and calculate the LCA results for future prospective.

# Selected Publications
For the detailed of these steps please cite the following publications.

# Scentific reference for step 1

Bernhard Steubing, Daniel de Koning, Adrian Haas, Christopher Lucien Mutel,
The Activity Browser — An open source LCA software building on top of the brightway framework,
Software Impacts,doi.org/10.1016/j.simpa.2019.100012.
https://www.softwareimpacts.com/article/S2665-9638(19)30012-0/fulltext

# Scentific reference for step 3

R. Sacchi, T. Terlouw, K. Siala, A. Dirnaichner, C. Bauer, B. Cox, C. Mutel, V. Daioglou, G. Luderer,
PRospective EnvironMental Impact asSEment (premise): A streamlined approach to producing databases for prospective life cycle assessment using integrated assessment models,
Renewable and Sustainable Energy Reviews,
Volume 160,2022.
doi.org/10.1016/j.rser.2022.112311.

# Scentific reference for step 4

Oberschelp, C., Pfister, S., Raptis, C.E. et al. Global emission hotspots of coal power generation. 
Nat Sustain 2, 113–121 (2019). https://doi.org/10.1038/s41893-019-0221-6

 # Generate .gml from Web of Science
 
 - VOS Viewer -> Bibliometric Network Viewer
 - Gephi -> Network Viewer (general) - Java 7
 - Web of Science - SCOPUS -> Get .ciw file from WoS
 - Citation report (interest by year) (save to EndNote desktop -> Full record)
 - With VOSViewer - create (map-biblio) (WoS) -> Choose Analysis (country, etc.) - Author -> Keyword Threshold
 - Save as GML (Graphic Markov Language). Problem: No direct way to look at individual papers
 
 ## Useful tpes of .gml
 
 - Co-cit+ref: most citations in total (references outside original .ciw file show up).
 - Bib+doc: most references to papers within original .ciw file (shared interests/most similar to your paper).
 - Cit+doc: most cited within the original .ciw file (most relevant papers).
 - Co-oc+auth-kw: actual kewords most used in .ciw file (keywords to use).
 - Co-oc+kw: connections between keywords in abstracts (sketch introduction using this).
 
 # Visualization of connections for .gml using Gephi
 
 - Gephi -> Data laboratory (from GML) -> Graph
 - Layout -> Yifan Hu proportional (good example).
 - Statistics (weights, degree) Rank
 - Modularity -> Finding community factor
 - Partition -> Modularity class
 - Click T in Graph
 
 - Set Degree Range in Filters next to Statisticd (rhs) (Topology) -> Move to queries below
 - Ego Network -> Direct connections (in filters)
 - Peripheral keywords (weakly coneected) e.g. RadioAstro <-> Site Testing
 
 
 - VOSViewer co-citation at beginning(author by author)
 - Directed (option in Gephi) -> Data Laboratory + Preview -> Statistics + Partitioning
 - Force Atlas 2 in Layout - use filter
 - Rank -> Max size + Modularity -> Right click -> Data Laboratory (1998 Rosenkranz - Radio Science)
 
 
 

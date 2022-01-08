# language_datasets
This repository holds all language datasets collected by the h2r lab over different papers at a single location with their respective papers.

# Note for I-DRAGGN Project:
For those completing the I-DRAGGN project, you will notice that that data in the RSS_2017_Arumugam_et_al paper isn't quite in the correct format that the I-DRAGGN paper describes. To work around this, it is necessary to preprocess the data manually. In my implementation of the project, I used the L0 dataset, and altered the L0.ml such that each line contained exactly 1 callable unit and 1 binding argument each.

For instance, a line reading "goNorth" could be altered to "goNorth 1" depending on the corresponding natural language command in the L0.en file.

/Prj2/
    * Data/: a git repository that contains data that is shared among more than one project
        * <Data1>/: a folder containing a set of related data files
            * README.md: a file describing how the raw data was obtained and processed
    * <Date>_<Prj>/: a git repository that contains a single project
        * README.md: a file that describes the project
        * Data/: contains data that is only used for this project
            * README.md: a file describing how the raw data was obtained and processed 
        * Res/:
            * <Date>_<Analysis>: contains the results of a single analysis, typically reported in a single file
        * Bin/: contains code that is used in multiple results folders

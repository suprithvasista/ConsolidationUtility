This is Preferred for easy use.

If Developer wants to leverage the functionality into his code they can just download 
    the pip version deployed and utilize it in there code base.

This utility lets users merge multiple xl sheets into consolidated xl's

There are some basic rules need to be followed while configuring the property file.
    1 Important Points to be considered before execution.
    2 Please provide the path eg: D: /folder/excel path.
    3 Default HeaderColumnvaluesIndex will be considered as ?0? if not provided.
    4 Please provide the Column name of index worksheet which contains all the worksheets name else default value for column will be considered as WorkSheetNames.
    5 Recommended: Please provide column name in IndexSheet which stores Column header for consolidation. Else please note the column headers will be picked from one of the sheets randomly.
    6 Default HeaderForConsolworksheet will be considered as '0' if not provided.
    7 TransPoseConsolidationRow to be provided if any transpose consolidation needs to be done exmaple 2,0,1 (2 represents number of rows to limit , 0 represents first column ,1 represents 1st column for transpose).
    8 Default ExcelOutPath will be considered as ConSolidated.xlsx.

There are two types of folders MacOsCosolidationUtility and WindowsConsolidationUtility.
    1 MacOsCosolidationUtility:
        Allows mac users to consolidate xl's by just executing the mac *Consolidation exec* file.
    2 WindowsConsolidationUtility:
        Allows windows users to execute the *ConsolidationUtility.exe* file. 

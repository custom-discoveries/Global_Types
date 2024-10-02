## Global Types
- The Global Types repository defines reusable vertices and edges for multiple graphs, allowing data to be loaded once and reused in specific local graphs. This ensures enterprise-wide data consistency and integrity, reducing redundancy.
- Global Types data is from the U.S. Census American Community Survey - Year 2022. The data includes Continent, Country, Region, Divison, State, County and City.

- As an exmaple: The BCBSA graph incoproates the Global_Type Vertexs: Region, Division, State. While using Global_Type Edges: hasDivision, hasStates. This allows the BCBSA graph to use only what is needed and not incropate any additonal data burdencies.
## Install and Run
### Install
To install this Global_Type demo, clone this repository at a terminal command prompt: 
- \>git clone https://github.com/custom-discoveries/Global_Types.git
### Run Cheetah in Cloned Directory:
-  cd Global_Types
-  Global_Types\> Cheetah [^1]
    - Select -b option to load both the schema & data
    - Note: The DDL scripts will create a temporary Graph to load the Global Data, once the data has been load, the temporary Graph is deleted. 
[^1]: See Cheetah [README.md](https://github.com/custom-discoveries/Cheetah/blob/main/README.md) for installation and setup of Cheetah

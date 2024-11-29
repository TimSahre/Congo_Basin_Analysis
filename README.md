
# **Congo Basin Wildlife Analysis**

## **Project Overview**
This project focuses on analyzing biodiversity in the Congo Basin using geospatial data. The goal is to analyze and visualize the habitat distribution of key species such as bonobos, chimpanzees, gorillas, forest elephants, and hippopotamuses. Using Python and libraries like `GeoPandas`, `Matplotlib`, and `Contextily`, high-resolution maps with the Mollweide projection are created to ensure accurate area representation.

---

## **Dataset Description**
- **MAMMALS**  
  The IUCN Digital Distribution Maps for Mammals contain spatial and attribute information about mammal species, including their geographic ranges.  
  **Link (Project Data):** [MAMMALS Dataset](https://drive.google.com/drive/folders/1fLYhp8MD0JtkRMrnQsHBjKrf3tZ36AlT?usp=drive_link)  
  **Original Source:** [IUCN Red List Spatial Data](https://www.iucnredlist.org/resources/spatial-data-download)

- **ne_10m_admin_0_countries**  
  This dataset provides administrative boundaries at the country level, used for background visualization.  
  **Link (Project Data):** [ne_10m_admin_0_countries Dataset](https://drive.google.com/drive/folders/1yFxOX_BxAXtBWo-ix6Qn8xCYa0E2JGRf?usp=drive_link)  
  **Original Source:** [Natural Earth Data](https://www.naturalearthdata.com/downloads/10m-cultural-vectors/)

---

## **Installation and Setup**
To run the project, ensure you have set up a suitable Python environment:

1. **Clone the Repository:**
   ```bash
   git clone git@github.com:TimSahre/Congo_Basin_Analysis.git
   cd Congo_Basin_Analysis
   ```

2. **Set Up the Conda Environment:**
   Install the required dependencies using the provided `environment.yml` file:
   ```bash
   conda env create -f environment.yml
   conda activate congo_basin_analysis
   ```

3. **Download the Data:**
   Download the shapefiles using the links provided above and save them in a `data/` folder within the project directory.

---

## **Key Features**
- **Data Filtering and Visualization**: Large datasets are efficiently filtered to focus the analysis on relevant species and regions, emphasizing the importance of data preparation for efficient processing.
- **Habitat Mapping**: Species habitats are displayed in distinct colors to highlight ecological patterns and relationships.
- **Actionable Insights**: Demonstrates how efficient data filtering and analysis techniques can contribute to conservation planning and biodiversity research.

---
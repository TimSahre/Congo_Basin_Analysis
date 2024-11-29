
# **Congo Basin Wildlife Analysis**

## **Project Overview**
This project focuses on analyzing biodiversity in the Congo Basin using geospatial data. The goal is to analyze and visualize the habitat distribution of key species such as bonobos, chimpanzees, gorillas, forest elephants, and hippopotamuses. Using Python and libraries like `GeoPandas`, `Matplotlib`, and `Contextily`, high-resolution maps with the Mollweide projection are created to ensure accurate area representation.

---

## **Dataset Description**
- **MAMMALS**  
  The IUCN Digital Distribution Maps for Mammals contain spatial and attribute information about mammal species, including their geographic ranges.  
  **Link:** [MAMMALS Dataset](https://drive.google.com/drive/folders/1fLYhp8MD0JtkRMrnQsHBjKrf3tZ36AlT?usp=drive_link)

- **ne_10m_admin_0_countries**  
  This dataset provides administrative boundaries at the country level, used for background visualization.  
  **Link:** [ne_10m_admin_0_countries Dataset](https://drive.google.com/drive/folders/1yFxOX_BxAXtBWo-ix6Qn8xCYa0E2JGRf?usp=drive_link)

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

## **Notebook Details**
The Jupyter Notebook **`Congo_Basin_Analysis.ipynb`** includes the following sections:

1. **Data Import:**  
   Loading the shapefiles and performing an initial inspection of the data structure.

2. **Projection:**  
   Transforming the data to the Mollweide projection to minimize area distortions.

3. **Visualization:**  
   Creating maps to depict the habitats of key wildlife species in the Congo Basin, including:
   - Overlaying species distributions with country boundaries.
   - Generating context maps with background data (e.g., country boundaries).

4. **Analysis:**  
   Identifying critical areas for conservation based on the geographic distribution of species.

---

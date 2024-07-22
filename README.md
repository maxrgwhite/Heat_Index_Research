# Heat_Index_Research

Hello. This code lets you compare Lu and Romps' (2022) Heat Index algorithm to others' (named in the notebooks. Lu and Romps' (2022) algorithm is available in Python, R, and Fortran code at https://romps.berkeley.edu/papers/pubs-2020-heatindex.html#:~:text=To%20extend%20the%20heat%20index,observable%20measure%20of%20physiological%20stress.

You will need some spatial data to run the code. I used ERA5-Land data at the hourly level for the Limpopo province of South Africa, with my  with a bounding box using this helpful tool: https://boundingbox.klokantech.com/.

The following notebooks (not python files – for your editing convenience) need to be executed in order:
1. 1_ERA5-Land_Data_Requests.ipynb
   - You will need a Copernicus account and to specify your [CDS API key]([url](https://ecmwf-projects.github.io/copernicus-training-c3s/cds-tutorial.html))
     ()
3. 2_Creating_and_concatenating_cubes.ipynb
4. 3_Cube_creation_frontend.ipynb
5. 4_Data_Analysis_frontend.ipynb

The first and third notebook can take a long time to run. For a Limpopo province sized region, the first notebook will take about 8 hours to run. think overnight for the first notebook, and 2+ days for the second notebook. Bare in mind that the secon 
Don't worry about the equivalent "backend" 

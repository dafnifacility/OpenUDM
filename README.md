# OpenUDM
Open repository for the Urban Development Model

## Basic inputs and outputs

Basic descriptions of the inputs and outputs of the UDM follow. 

See the [Data](/Data) folder for examples of these files.

### Input files

| File Name | Type | Description 
| :-------- | :--- | :---------- 
| in_mce_ras_dbl | CSV | Table of ‘double precision’ rasters for cell suitability calculation 
| in_mce_ras_int | CSV | Table of ‘integer’ rasters for cell suitability calculation
| in_params | CSV | General model parameters
| in_udm_ras | CSV | Table of ‘integer’ rasters for UDM
| in_zonal_density | CSV | Optional density value for each zone
| in_zonal_pop | CSV | Initial and Final population values for each zone
| in_zone_order | CSV | Zones ordered by label
| raster_header | HDR (txt) | Header information for .asc raster inputs.


### Output files
| File name | Type | Description 
| :-------- | :--- | :---------- 
| out_cell_dev | ASC | Land development raster
| out_cell_metadata | CSV | Model inputs and parameters for current run
| out_cell_overflow | CSV | Various reporting measures e.g. density adjustments required

# Export Network from Map

Export the graph used by the openrouteservice for routing calculations for a given extent.

## Parameters

| Label                              | Name             | Type                            | Description                                                                                                                                                                                                                                                                           |
|------------------------------------|------------------|---------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Provider                           | `INPUT_PROVIDER` | [enumeration] <br /> Default: 0 | The provider to use. See [Adding Providers](/installation_and_setup.md#adding-providers)                                                                                                                                                                                              |
| Travel mode                        | `INPUT_PROFILE`  | [enumeration] <br /> Default: 0 | The mode of travel to use. One of:  <ul><li>0 - driving-car</li><li>1 - driving-hgv</li><li>2 - cycling-regular</li><li>3 - cycling-road</li><li>4 - cycling-mountain</li><li>5 - cycling-electric</li><li>6 - foot-walking</li><li>7 - foot-hiking</li><li>8 - wheelchair</li> </ul> |
| Input Extent                       | `INPUT_EXTENT`   | [extent]                        | The extent of the export.                                                                                                                                                                                                                                                             |
| Node export                        | `OUTPUT_POINT`   | [vector: geometry]              | Resulting vector grid layer. TODO                                                                                                                                                                                                                                                     |
| Network_Export_YYYY-MM-DD-HH:MM:SS | `OUTPUT`         | [vector: geometry]              | Resulting vector grid layer. TODO                                                                                                                                                                                                                                                     |


## Outputs

| Label                              | name           | Type               | Description                       |
|------------------------------------|----------------|--------------------|-----------------------------------|
| Node export                        | `OUTPUT_POINT` | [vector: geometry] | Resulting export                  |
| Network_Export_YYYY-MM-DD-HH:MM:SS | `OUTPUT`       | [vector: geometry] | Resulting vector grid layer. TODO |

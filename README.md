# LivingPark utils

A collection of utility functions to write LivingPark notebooks.

Usage examples:

```
import livingpark_utils

utils = livingpark_utils.LivingParkUtils('scherfler-etal')
utils.prologue()
utils.download_ppmi_metadata(['Demographics.csv'])
utils.find_nifti_file_in_cache(x['PATNO'], x['EVENT_ID'], x['Description'])
utils.disease_duration()
```

See also [contributing guidelines](https://github.com/LivingPark-MRI/documentation).

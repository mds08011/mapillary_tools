**This repository is a fork of Mapillary_Tools with the Interpolate Directions command altered.**

### Derive image direction and Upload
 - Derive image direction (image heading or camera angle) based on image latitude and longitude. If images are missing direction, the direction is derived automatically, if direction is present, it will be derived and overwritten only if the flag `--interpolate directions` is specified.

 ```bash
mapillary_tools process --advanced --import_path "path/to/images" --user_name username_at_mapillary --interpolate_directions
mapillary_tools upload --import_path "path/to/images"
```

or

 ```bash
mapillary_tools process_and_upload --advanced --import_path "path/to/images" --user_name username_at_mapillary --interpolate_directions
```


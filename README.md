### `map_server`

#### Notes
1. The instructions for `map_server` showed `History Policy = Keep Last` for the `Map` topic `/map`, but the config file for [`cartographer_slam`](https://github.com/ivogeorg/cartographer_slam.git) works fine, and there `History Policy = Keep All`.
2. The `map_server` package [launches]() a `nav2_lifecycle_manager` node.


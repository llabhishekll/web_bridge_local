# Web Bridge Local

This repository contains supporting code, for a comprehensive understanding and additional details, refer main repository [here](https://github.com/llabhishekll/tortoisebot_docker).

## Structure

```text
.
├── README.md
├── async_web_server_cpp
│   ├── CHANGELOG.rst
│   ├── CMakeLists.txt
│   ├── LICENSE
│   ├── README.md
│   ├── include
│   │   └── async_web_server_cpp
│   ├── package.xml
│   ├── src
│   │   ├── http_connection.cpp
│   │   ├── http_reply.cpp
│   │   ├── http_request.cpp
│   │   ├── http_request_handler.cpp
│   │   ├── http_request_parser.cpp
│   │   ├── http_server.cpp
│   │   ├── websocket_connection.cpp
│   │   ├── websocket_message.cpp
│   │   └── websocket_request_handler.cpp
│   └── test
│       ├── CMakeLists.txt
│       ├── simple_http_requests_test.py
│       ├── test.html
│       ├── test_dir
│       ├── test_web_server.cpp
│       ├── tests.test
│       └── websocket_test.py
├── web_bridge
│   ├── CMakeLists.txt
│   ├── action
│   │   ├── ExampleAction.action
│   │   └── WaypointAction.action
│   ├── launch
│   │   ├── mapping.launch
│   │   ├── project.launch
│   │   ├── sim_hector_obstacles.launch
│   │   ├── sim_husky_clearpath_playpen.launch
│   │   ├── sim_turtlebot2_clearpath_playpen.launch
│   │   ├── sim_turtlebot2_empty.launch
│   │   ├── tf2_web.launch
│   │   └── web.launch
│   ├── package.xml
│   └── scripts
│       ├── example_action_server.py
│       ├── example_services.py
│       ├── hector_services_copy.py
│       ├── robot_params.py
│       └── tortoisebot_action_server.py
└── web_video_server
    ├── AUTHORS.md
    ├── CHANGELOG.rst
    ├── CMakeLists.txt
    ├── LICENSE
    ├── README.md
    ├── include
    │   └── web_video_server
    ├── mainpage.dox
    ├── package.xml
    └── src
        ├── h264_streamer.cpp
        ├── image_streamer.cpp
        ├── jpeg_streamers.cpp
        ├── libav_streamer.cpp
        ├── multipart_stream.cpp
        ├── png_streamers.cpp
        ├── ros_compressed_streamer.cpp
        ├── vp8_streamer.cpp
        ├── vp9_streamer.cpp
        └── web_video_server.cpp
```

## License

Distributed under the original developer's license. See `LICENSE.txt` for more information.

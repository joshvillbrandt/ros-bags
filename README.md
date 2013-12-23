ros-bags
========

Some useful ROS bags. Visit http://wiki.ros.org/Bags for more information.

## Bags

| File Name | Description | Date |
| --- | --- | --- |
| `ilab_fast.bag` | Mecanumbot laser scan data (XV-11 laser) taken while driving quickly around the USC iLab hallway loop. | 2013/01/09 |
| `ilab_slow.bag` | Mecanumbot laser scan data (XV-11 laser) taken while driving slowly around the USC iLab hallway loop. | 2013/01/09 |
| `red_ball.bag` | Mecanumbot point cloud data (Microsoft Kinect) taken of two red ball of different sizes. | 2013/12/22 |

## Usage

The `red_ball.bag` bag only contains one frame of point cloud data. One can loop playback with the `-l` option:

	rosbag play -l red_ball.bag


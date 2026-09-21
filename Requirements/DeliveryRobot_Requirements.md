
| Req-Id | Description                                                                                          | Priority |


| R-01   | The robot should remain idle after being switched on until it receives a delivery request.          | High     |

| R-02   | When a delivery request is received, the robot should start moving toward the destination.         | High     |
| R-03   | While moving, the robot should continuously check for obstacles around it.                          | High     |
| R-04   | If an obstacle is detected, the robot should stop normal navigation and enter obstacle avoidance.  | High     |
| R-05   | After avoiding the obstacle, the robot should continue moving toward the destination.               | High     |
| R-06   | When the robot reaches the destination, it should start the delivery process.                       | High     |
| R-07   | After the package is delivered successfully, the robot should return to the warehouse.             | High     |
| R-08   | If the battery becomes critically low during navigation, the robot should stop and return to the  | High     |
 warehouse.                                                                                        
| R-09   | After reaching the warehouse, the robot should become idle and wait for another delivery request. | Medium   |
| R-10   | The robot should not start delivery directly from the idle state or while avoiding an obstacle.    | High     |

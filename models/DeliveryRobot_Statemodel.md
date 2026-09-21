
| State_Id | State_Name         | Description                          | Entry Condition      | Exit Condition       |


| S-01     | IDLE               | Waiting for a delivery request.      | Robot is switched on | Request received     |


| S-02     | NAVIGATING         | Moving toward the destination.       | Request received     | Destination reached, |


|          |                    |                                      |                      | obstacle detected,   |


|          |                    |                                      |                      | or battery critical  |


| S-03     | AVOIDING_OBSTACLE  | Avoiding an obstacle in the path.   | Obstacle detected    | Obstacle avoided      |


| S-04     | DELIVERING         | Delivering the package.              | Destination reached  | Package delivered     |


| S-05     | RETURNING          | Returning to the warehouse.          | Package delivered or | Warehouse reached     |


|          |                    |                                      | battery critical     |                      |


| S-06     | IDLE               | Waiting for another delivery.        | Warehouse reached    | New request received |


| S-07     | NAVIGATING         | Continuing after obstacle avoidance. | Obstacle avoided     | Destination reached  |


|          |                    |                                      |                      | or obstacle detected |


| S-08     | AVOIDING_OBSTACLE  | Temporarily avoiding an obstacle.    | Obstacle detected    | Obstacle avoided      |


| S-09     | RETURNING          | Returning due to low battery.        | Battery critical     | Warehouse reached     |
| S-10     | DELIVERING         | Completing the delivery process.     | Destination reached  | Delivery successful   |

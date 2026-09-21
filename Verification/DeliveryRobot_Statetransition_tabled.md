

| Transition_Id  | From State           | Event                    | To State             | Req-Id |
| T-01           | IDLE                 | Delivery Request         | NAVIGATING           | R-02   |
|                |                      | Received                 |                      |        |
| T-02           | NAVIGATING           | Obstacle Detected        | AVOIDING_OBSTACLE    | R-04   |
| T-03           | AVOIDING_OBSTACLE    | Obstacle Avoided         | NAVIGATING           | R-05   |
| T-04           | NAVIGATING           | Destination Reached     | DELIVERING           | R-06   |
| T-05           | DELIVERING           | Delivery Successful     | RETURNING            | R-07   |
| T-06           | NAVIGATING           | Critical Battery        | RETURNING            | R-08   |
| T-07           | RETURNING            | Warehouse Reached       | IDLE                 | R-09   |
| T-08           | IDLE                 | Delivery Request        | NAVIGATING           | R-02   |
|                |                      | Received                 |                      |        |
| T-09           | NAVIGATING           | Obstacle Detected        | AVOIDING_OBSTACLE    | R-04   |
| T-10           | AVOIDING_OBSTACLE    | Obstacle Avoided         | NAVIGATING           | R-05   |


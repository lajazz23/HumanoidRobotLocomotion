# Description of Project

We are testing the baseline RL model, `skrl`, in its ability to train a robot on basic locomotion. By examining its capabilities, we can better understand applications of RL in real-world robotics.

## Joint Indices
 
Knowing the joint indices can be very helpful in changing reward parameters and customizing training.

### Unitree G1
The Unitree G1 robot in Isaac Sim comes pre-configured with a total of 37 joints:

| Index| Joint Name         |   Index |  Joint Name      |  Index  |  Joint Name  |  Index  | Joint name  |
|------|:-------------------| --------|:-----------------| --------|:-------------|---------|:------------|
|   0  |left hip pitch      |    12   |right knee        |    24   |left three    |    36   |   right two |
|   1  |right hip pitch     |    13   |left shoulder yaw |    26   |left zero     |
|   2  |torso               |    14   |right shoulder yaw|    27   |right five    |
|   3  |left hip roll       |    15   |left ankle pitch  |    28   |right three   |
|   4  |right hip roll      |    16   |right ankle pitch |    29   |right zero    |
|   5  |left shoulder pitch |    17   |left elbow pitch  |    30   |left six      |
|   6  |right shoulder pitch|    18   |right elbow pitch |    31   |left four     |
|   7  |left hip yaw        |    19   |left ankle roll   |    32   |left one      |
|   8  |right hip yaw       |    20   |right ankle roll  |    33   |right six     |
|  9   |left shoulder roll  |    21   |left elbow roll   |    34   |right four    |
|  10  |right shoulder roll |    22   |right elbow roll  |    35   |right one     |
|  11  |left knee           |    23   |left five         |    36   |left two      |

### Unitree H1
The Unitree H1 comes in Isaac Sim with just 19 joints:

| Index| Joint Name      |   Index |  Joint Name        | 
|------|:----------------| --------|:-------------------| 
|   0  |left hip yaw     |    10   |right ankle         | 
|   1  |right hip yaw    |    11   |left shoulder pitch |   
|   2  |torso            |    12   |right shoulder pitch|   
|   3  |left hip roll    |    13   |left shoulder roll  |   
|   4  |left hip pitch   |    14   |left shoulder yaw   |   
|   5  |left knee        |    15   |left elbow          |    
|   6  |left ankle       |    16   |right shoulder roll |    
|   7  |right hip roll   |    17   |right shoulder yaw  |    
|   8  |right hip pitch  |    18   |right elbow         |
|  9   |right knee       |
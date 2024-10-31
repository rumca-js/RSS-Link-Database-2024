# Source:Boston Dynamics, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UC7vVhkEfw4nOGp8TyDk7RcQ, language:en

## Atlas Goes Hands On
 - [https://www.youtube.com/watch?v=F_7IPm7f1vI](https://www.youtube.com/watch?v=F_7IPm7f1vI)
 - RSS feed: $source
 - date published: 2024-10-30T13:44:10+00:00

Atlas is autonomously moving engine covers between supplier containers and a mobile sequencing dolly. The robot receives as input a list of bin locations to move parts between. 

Atlas uses a machine learning (ML) vision model to detect and localize the environment fixtures and individual bins [0:36]. The robot uses a specialized grasping policy and continuously estimates the state of manipulated objects to achieve the task.

There are no prescribed or teleoperated movements; all motions are generated autonomously online. The robot is able to detect and react to changes in the environment (e.g., moving fixtures) and action failures (e.g., failure to insert the cover, tripping, environment collisions [1:24]) using a combination of vision, force, and proprioceptive sensors.


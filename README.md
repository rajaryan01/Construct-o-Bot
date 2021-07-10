# Construct-o-Bot
This is a E-Yantra Project .In which we have made an robot which follow the path according to given coordinates and perform the given operations(like Pick the Box , Place the Box etc.).
construct-o-bot
Environmental conditions such as extreme rainfall, earthquakes, landslides and floods often cause natural disasters which lead to tremendous loss of life and property, causing great disruption in people’s lives and the economy. In 2018, across the world there were 315 natural disaster events recorded with 11,804 deaths, over 68 millions of people were affected, and 131.7 billion dollars in economic losses.

After a disaster strikes, governments and private organizations engage in reconstruction efforts of infrastructure, such as roads, bridges, power and railway lines, houses etc. This is a very labor and capital-intensive task. Moreover, doing this at a disaster site, with its multiple associated risks and challenging terrain, poses an additional challenge. Motivated by this scenario, in order to help the needy victims in the affected areas, this edition of e-Yantra Robotics Competition (eYRC 2019-20) presents the theme “Construct-O-Bot”.

In this theme, the arena is an abstraction of a disaster site where the robot picks the construction material and traverses paths in order to deposit it at the site to be reconstructed. In order to maneuver over these paths, the Construct-O-Bot has to use intelligent line-following and path-planning algorithms to reach safely and quickly using shortest paths. After reaching the site, the Construct-O-Bot carefully has to place the material at the required positions which may include placing the material at different heights from the ground. It has to deposit all required material at multiple construction sites, navigating through various terrains.

**Line following algorithm**
we have to follow the lines and detecting the nodes properly the main difficulty we were facing was that width of line was too less (1.2 cm)while the distance between adjacent sensor was 1.8 cm . we made algorithms to properly follow the line and detect nodes we also made algorithms for different lines such as white line on black surface,broken lines at last we also worked on wall following

**Path-indicator-using-Dijkstra**
In this ,i divided whole arena into nodes shown in pdf (image of arena). I started first node as a 0 and last node as a 15(total 16 nodes) .Counting is started from left lower side and end at right upper side.

For More details of Project- https://www.irjet.net/archives/V8/i2/IRJET-V8I2179.pdf

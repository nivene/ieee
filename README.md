# WKU IEEE Robot 2025
The WKU IEEE Robot is a EE/ME Senior Project. This is a repository for our (robot_ws). 
## Utilizing Github with the project:
Run these commands to accomplish your task. Make sure that you are in the `robot_ws` when you try to push anything. 


git branch -M main
git push -u origin main
## or 

    echo "# ieee" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin git@github.com:nivene/ieee.git
    git push -u origin main


    source /opt/ros/<ros_distro>/setup.bash
    cd /tmp
    wget https://raw.githubusercontent.com/linorobot/linorobot2/${ROS_DISTRO}/install_linorobot2.bash
    bash install_linorobot2.bash <robot_type> <laser_sensor> <depth_sensor>

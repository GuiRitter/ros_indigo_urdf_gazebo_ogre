# ros_indigo_urdf_gazebo_ogre
Test package containing all attemps at using custom OGRE materials in URDF in ROS Indigo that displays in Gazebo

I added the following to `/usr/share/gazebo-2.2/media/materials/scripts/gazebo.material`:

```
material ros_indigo_urdf_gazebo_ogre/InternationalOrange
{
  technique
  {
    pass ambient
    {
      ambient 1 0.3098039215686274 0
      diffuse 1 0.3098039215686274 0
      specular 0.1 0.1 0.1 1 1
    }
  }
}
```

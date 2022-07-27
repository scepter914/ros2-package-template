# ros2_package_template

This is my ROS2 package template with Autoware.
Original repository is <https://github.com/kenji-miyake/ros2_package_template> and customize for myself.
If you use for Autoware development, you should use CMakeLists_autoware.txt and package_autoware.xml.


## Usage

- Install

```sh
brew install fd sd rename
```

- Use this tempalate

```sh
cd YOUR_ROS_WORKSPACE
git clone git@github.com:scepter914/ros2_package_template.git YOUR_PACKAGE_NAME
cd YOUR_PACKAGE_NAME

# case1. If you'd like to cleanup manually
./setup.fish
mv PACKAGE_README.md README.md
rm setup.fish
rm -rf .git # When you add this to an existing repository

# case2. If you'd like to cleanup automatically
./setup.fish --clean
```



# Box2D CMake Support

This is a wrapper around the C++ library [Box2D](http://box2d.org/). The Source code can be found on [Github](https://github.com/erincatto/Box2D)

## Usage
### Add as Submodule

```sh
cd $PROJECT_ROOT
git submodule add https://github.com/anteroul/Box2D-cmake.git 3rd_party/Box2D-cmake
git submodule update --init --recursive
```

### Use

In CMakeLists.txt:

```
add_subdirectory(3rd_party/Box2D-cmake)
target_link_libraries(${PROJECT_NAME} anteroul::Box2D)
```

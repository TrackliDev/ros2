# ROS 2

Official documentation is at https://docs.ros.org

## Dependencies:

All dependecies should be resolved by following the installation steps proposed on the [official tutorial](https://docs.ros.org/en/humble/Installation/Alternatives/Ubuntu-Development-Setup.html). But, to improve dependency control, we listed bellow the complete software BOM (Bill Of Materials) for the ROS 2 version used by Trackli:

<center>

|ID |Dependency                 |Version|
|---|---------------------------|-------|
|1  |Ubuntu Linux               |20.04                        |
|2  |python3-pydot              |1.4.1-3                      |
|3  |python3-numpy              |1:1.17.4-5ubuntu3.1          |
|4  |python3-lttng              |2.11.2-1build1               |
|5  |python3-setuptools         |45.2.0-1ubuntu0.1            |
|6  |python3-dev                |3.8.2-0ubuntu2               |
|7  |python3-pygraphviz         |1.5-4build1                  |
|8  |clang-tidy                 |1:10.0-50~exp1               |
|9  |python3-pytest-cov         |2.8.1-1                      |
|10 |libxaw7-dev                |2:1.0.13-1                   |
|11 |libtinyxml2-dev            |7.0.0+dfsg-1build1           |
|12 |libopencv-dev              |4.2.0+dfsg-5                 |
|13 |pydocstyle                 |2.1.1-1                      |
|14 |libasio-dev                |1:1.12.2-1                   |
|15 |python3-psutil             |5.5.1-1ubuntu4               |
|16 |libbullet-dev              |2.88+dfsg-2build2            |
|17 |libatomic1                 |10.3.0-1ubuntu1~20.04        |
|18 |uncrustify                 |0.69.0+dfsg1-1build1         |
|19 |libqt5core5a               |5.12.8+dfsg-0ubuntu2.1       |
|20 |libbenchmark-dev           |1.5.0-4build1                |
|21 |python3-argcomplete        |1.8.1-1.3ubuntu1             |
|22 |doxygen                    |1.8.17-0ubuntu2              |
|23 |libignition-math6-dev      |6.13.0-1~focal               |
|24 |python3-packaging          |20.3-1                       |
|25 |libgl1-mesa-dev            |21.2.6-0ubuntu0.1~20.04.2    |
|26 |libglu1-mesa-dev           |9.0.1-1build1                |
|27 |liborocos-kdl-dev          |1.4.0-7ubuntu1               |
|28 |python3-lark               |0.8.1-1                      |
|29 |libsqlite3-dev             |3.31.1-4ubuntu0.5            |
|30 |pybind11-dev               |2.4.3-2build2                |
|31 |pkg-config                 |0.29.1-0ubuntu4              |
|32 |openssl                    |1.1.1f-1ubuntu2.19           |
|33 |libxml2-utils              |2.9.10+dfsg-5ubuntu0.20.04.6 |
|34 |python3-pytest-mock        |1.10.4-3                     |
|35 |python3-lxml               |4.5.0-1ubuntu0.5             |
|36 |python3-netifaces          |0.10.4-1ubuntu4              |
|37 |clang-format               |1:10.0-50~exp1               |
|38 |libcunit1-dev              |2.1-3-dfsg-2build1           |
|39 |cppcheck                   |1.90-4build1                 |
|40 |libqt5svg5                 |5.12.8-0ubuntu1              |
|41 |python3-pytest             |4.6.9-1                      |
|42 |python3-importlib-metadata |1.5.0-1                      |
|43 |libspdlog-dev              |1:1.5.0-1                    |
|44 |python3-pil                |7.0.0-4ubuntu0.7             |
|45 |libpyside2-dev             |5.14.0-1~exp1ubuntu5         |
|46 |libshiboken2-dev           |5.14.0-1~exp1ubuntu5         |
|47 |pyqt5-dev                  |5.14.1+dfsg-3build1          |
|48 |python3-pyqt5              |5.14.1+dfsg-3build1          |
|49 |python3-pyqt5.qtsvg        |5.14.1+dfsg-3build1          |
|50 |python3-pyside2.qtsvg      |5.14.0-1~exp1ubuntu5         |
|51 |python3-sip-dev            |4.19.21+dfsg-1build1         |
|52 |shiboken2                  |5.14.0-1~exp1ubuntu5         |
|53 |python3-babeltrace         |1.5.8-1build1                |
|54 |libcurl4-openssl-dev       |7.68.0-1ubuntu2.18           |
|55 |curl                       |7.68.0-1ubuntu2.18           |
|56 |libqt5widgets5             |5.12.8+dfsg-0ubuntu2.1       |
|57 |libyaml-cpp-dev            |0.6.2-4ubuntu1               |
|58 |graphviz                   |2.42.2-3build2               |
|59 |python3-pytest-timeout     |1.3.3-2                      |
|60 |libzstd-dev                |1.4.4+dfsg-3ubuntu0.1        |
|61 |python3-pykdl              |1.4.0-7ubuntu1               |
|62 |pyflakes3                  |2.1.1-2ubuntu1               |
|63 |python3-matplotlib         |3.1.2-1ubuntu4               |
|64 |libxrandr-dev              |2:1.5.2-0ubuntu1             |
|65 |libqt5svg5-dev             |5.12.8-0ubuntu1              |
|66 |libassimp-dev              |5.0.1~ds0-1build1            |
|67 |acl                        |2.2.53-6                     |
|68 |libacl1-dev                |2.2.53-6                     |
|69 |libqt5opengl5              |5.12.8+dfsg-0ubuntu2.1       |
|70 |git                        |1:2.25.1-1ubuntu3.11         |
|71 |file                       |1:5.38-4                     |
|72 |python3-cairo              |1.16.2-2ubuntu2              |
|73 |libfreetype6               |2.10.1-2ubuntu0.3            |
|74 |cmake                      |3.16.3-1ubuntu1.20.04.1      |
|75 |python3-yaml               |5.3.1-1ubuntu0.1             |
|76 |python3-pkg-resources      |45.2.0-1ubuntu0.1            |
|77 |libtinyxml-dev             |2.6.2-4build1                |
|78 |libx11-dev                 |2:1.6.9-2ubuntu1.5           |
|79 |libeigen3-dev              |3.3.7-2                      |
|80 |python3-flake8             |3.7.9-2                      |
|81 |python3-pycodestyle        |2.5.0-2                      |
|82 |libconsole-bridge-dev      |0.4.4+dfsg-1build1           |
|83 |libyaml-dev                |0.2.2-1                      |
|84 |python3-cryptography       |2.8-3ubuntu0.1               |
|85 |python3-catkin-pkg-modules |0.5.2-1                      |
|86 |libssl-dev                 |1.1.1f-1ubuntu2.19           |
|87 |python3-empy               |3.3.2-5.1                    |
|88 |python3-mypy               |0.761-1build1                |
|89 |python3-rosdistro-modules  |0.9.0-1                      |
|90 |qtbase5-dev                |5.12.8+dfsg-0ubuntu2.1       |
|91 |libqt5gui5                 |5.12.8+dfsg-0ubuntu2.1       |
|92 |libignition-cmake2-dev     |2.15.0-1~focal               |
|93 |python3-minimal            |3.8.2-0ubuntu2               |
|94 |libfreetype6-dev           |2.10.1-2ubuntu0.3            |
|95 |tango-icon-theme           |0.8.90-7                     |

</center>

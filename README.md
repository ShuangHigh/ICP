# ICP
带可视化的点云配准程序
midir build
cd build
cmake ..
make

build/icp path_of_source path_of_target num_of_iteration

先迭代num_of_iteration次后,显示
然后每按一次空格,迭代一次

# SuperSudoku
> Date:2018.12  
> Author:FSMM

## 项目介绍
1. 数独生成器
    * 生成数独
      生成给定数量的数独到sudoku.txt文件中，数量范围(1≤N≤1000000)  
      运行命令：sudoku.exe -c number
    * 数独求解  
      读取数独文件，格式如下，将求解得到的数独输出到sudoku.txt中  
        9	0	8	0	6	0	1	2	4   
        2	3	7	4	5	1	9	6	8   
        1	4	6	0	2	0	3	5	7   
        0	1	2	0	7	0	5	9	3   
        0	7	3	0	1	0	4	8	2   
        4	8	0	0	0	5	6	0	1   
        7	0	4	5	9	0	8	1	6   
        8	9	0	7	4	6	2	0	0   
        3	0	5	0	8	0	7	0	9  
      运行命令：sudoku.exe -s puzzle_path
2. 数独游戏界面
    * 选择难度等级：初级 中级 高级
    * 选中空格位置，选择数字或键盘输出填空
    * 当前错误填写标红警示
    * 求解成功后弹出提示
    
## 开发环境
* 64bit windows10
* visual studio 2017
* qt 5.12.0
* 语言C++
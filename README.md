# wheel_tokyo_weili
使用wheel_planner.msg進行控制機器人
topic名稱 /wheel/planner

distance_x y z(單位:公分)
決定機器人的移動方向跟移動距離

velocity_x y z(xy速度最快不要超過0.5，z最多不要超過1)
決定機器人的移動方向(持續給值會一直前進，給0會停止)

far_left far_right (bool)
true決定移動到最左邊或最右邊場地
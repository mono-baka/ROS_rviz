# 自作したロボットをRvizで表示
## 準備
catkin_ws/src以下にgit clone　
packageをビルドする　
current directoryをcatkin_ws/srcにしてターミナルで 
catkin_create_pkg ROS_rviz std_msg rospy roscpp tf 
を実行
![](/img/ddd.png) 
xmlとtxtファイルが作られる 

## 使い方
 launchフォルダを開きそこでターミナルを開く（cdコマンドでlaunchフォルダまで移動しても可） 
 ![](/img/aaa.png) 
 display.txtに打つべきコマンドが入っているのでターミナルへコピペし実行 
 ↓display.txtに入ってるコマンド 
 roslaunch my_robo_description display.launch 
 
 この時点ではエラーが出て表示されない（原因はよくわからない）　
![](/img/bbb.png) 
 
右上のFile->open configでrvizフォルダのurdf.rvizを開き初期設定をすると... 
![](/img/ccc.png) 
以上

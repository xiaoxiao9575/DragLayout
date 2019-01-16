# DragLayout
一个悬浮可拖动的layout，实现其子view的拖动，拖动到任意位置都不影响点击。
![image](https://github.com/xiaoxiao9575/DragLayout/blob/master/gif/dragLayout.gif)

一、接入方法：
1，在app的build.gradle添加

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

2，在app的build.gradle添加

	dependencies {
	        implementation 'com.github.xiaoxiao9575:DragLayout:1.0.0'
	}

二、使用方法：

    <com.github.gjp.draglayout.DragLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <ImageView
            android:id="@+id/imageView"
            android:layout_width="60dp"
            android:layout_height="60dp"
            android:src="@mipmap/ic_launcher_round"
            />

    </com.github.gjp.draglayout.DragLayout>

三、如果使用中存在问题和建议请在我的CSDN中留言
https://blog.csdn.net/weixin_40998254/article/details/86513643




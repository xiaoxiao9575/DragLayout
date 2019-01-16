# DragLayout

[README 中文版](https://github.com/xiaoxiao9575/DragLayout/blob/master/README.md)

the view in DragLayout can be easily dragged anywhere and click events are unaffected.
![image](https://github.com/xiaoxiao9575/DragLayout/blob/master/gif/dragLayout.gif)

## HOW TO INTEGRATE：
### 1，Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

### 2，Add the dependency:

	dependencies {
	        implementation 'com.github.xiaoxiao9575:DragLayout:1.0.0'
	}

## HOW TO USE：

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

## If you have any problems and Suggestions, please leave messages in my CSDN.
https://blog.csdn.net/weixin_40998254/article/details/86513643





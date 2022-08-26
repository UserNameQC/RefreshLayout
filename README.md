# RefreshLayout
###project build.gradle 中添加
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

app  build.gradle 中添加
implementation 'com.github.UserNameQC:RefreshLayout:0.0.1'

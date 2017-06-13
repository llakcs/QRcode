# QRcode
转载别人的代码修改了一下，方便自己使用!原文地址:https://github.com/bingoogolapple/BGAQRCode-Android



how to use 

Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency

	dependencies {
	        compile 'com.github.llakcs:QRcode:1.0'
	}

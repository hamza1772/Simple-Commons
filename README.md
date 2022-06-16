# Simple Commons
Some helper functions, dialogs etc used by multiple simple apps.</br>
For reporting bugs/features that affect multiple apps please use the <a href="https://github.com/SimpleMobileTools/General-Discussion">General Discussion</a> repository.

**Library available at JitPack.io**

[![](https://jitpack.io/v/hamza1772/Simple-Commons.svg)](https://jitpack.io/#hamza1772/Simple-Commons)

## Setup
The simplest way to use AlertDialog is to add the library as dependency to your build.

## Gradle

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.hamza1772:Simple-Commons:1.0.0'
	}

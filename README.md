# Better lang reader

## Summary

"Lang files with less crong"
basically this allows you to have more organized lang files such as:
```json:
    {
        "something":{
            "thing":"thingy"
        }   
    }
```
and to get "thingy", you can use the usual TranslatableText for "something.thing"

## Use
add to repositories
```
repositories {
	//...
	maven { url 'https://jitpack.io' }
	//...
}
```
add this to dependencies
```
dependencies {
    	//...
    	implementation 'com.github.geekazodium:better-lang-reader:main-SNAPSHOT'
	//...
}
```

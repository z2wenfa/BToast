# BToast

 [![Download](https://api.bintray.com/packages/bsss/maven/BToast/images/download.svg) ](https://bintray.com/bsss/maven/BToast/_latestVersion)
 
 an Toast Util For Android!
 
### Show And Usage

#### base
  
  To display an success Toast：
  
   ```Java
   BToast.success(v.getContext())
            .text("this is text")
            .show();
   ```
   
   ![](https://github.com/bravinshi/ImJack/blob/master/BToast_screen_cup/success.jpg) 
  
  
  To display an animate success Toast：
  
  ```Java
   BToast.success(v.getContext())
            .text(R.string.text_test_content)
            .animate(true)
            .show();
   ```
  ![](https://github.com/bravinshi/ImJack/blob/master/BToast_screen_cup/animate_success.gif) 
  
  
  To display an success Toast with target(View)：
  ```Java
   BToast.success(v.getContext())
            .text(R.string.text_test_content)
            .target(target)
            .show();
   ```
  ![](https://github.com/bravinshi/ImJack/blob/master/BToast_screen_cup/layout_bottom.jpg) 
  
  
#### more

To display an error Toast：
  
   ```Java
   BToast.error(v.getContext())
            .text(R.string.text_test_content)
            .show();
   ```
   
   ![](https://github.com/bravinshi/ImJack/blob/master/BToast_screen_cup/error.jpg) 
   
   To display an info Toast：
  
   ```Java
   BToast.info(v.getContext())
            .text(R.string.text_test_content)
            .show();
   ```
   
   ![](https://github.com/bravinshi/ImJack/blob/master/BToast_screen_cup/info.jpg) 
   
   To display an waring Toast：
  
   ```Java
   BToast.waring(v.getContext())
            .text(R.string.text_test_content)
            .show();
   ```
   
   ![](https://github.com/bravinshi/ImJack/blob/master/BToast_screen_cup/waring.jpg) 
   
   To display an normal Toast：
  
   ```Java
   BToast.normal(v.getContext())
            .text(R.string.text_test_content)
            .show();
   ```
   
   ![](https://github.com/bravinshi/ImJack/blob/master/BToast_screen_cup/normal.jpg) 
  
 
### Dependency
 
#### 1
 
 ```Java
 buildscript {
    repositories {
        ...
        jcenter()
    }
    dependencies {
       ...
    }
 }
```

### 2
 
  ```Java
 dependencies {
    ...
    implementation 'com.bravin.btoast:BToast:1.0.0'
 }
 ```

 
# LayoutFilesInSubfolders


![alt text](https://github.com/harunkor/LayoutFilesInSubfolders/blob/master/ss2021-11-27%2020.55.46.png?raw=true)



You can create a new folder inside the res directory. The new folder you create can be your res source.

Open app build.gradle file and add the following code

```

sourceSets {
    main {
        res.srcDirs =
                [
                        'src/main/res/layouts/activities',
                        'src/main/res/layouts/fragements',
                        'src/main/res/layouts/includes',
                        'src/main/res/layouts/items',
                        'src/main/res/layouts',
                        'src/main/res'
                ]
    }
}
```




#Happy coding 💪


https://stackoverflow.com/questions/70134272/inside-layout-folder-create-multiple-folder-android-studio/

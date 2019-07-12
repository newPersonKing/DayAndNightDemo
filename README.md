# DayAndNightDemo
AppCompatDelegate 实现主题切换 
实现原理 是通过设置两套资源文件 通过AppCompatDelegate来切换不同的模式
```swift
    btn_change.setOnClickListener {
            if(AppCompatDelegate.getDefaultNightMode() == AppCompatDelegate.MODE_NIGHT_NO){
                   AppCompatDelegate.setDefaultNightMode(AppCompatDelegate.MODE_NIGHT_YES)
            }else{
                AppCompatDelegate.setDefaultNightMode(AppCompatDelegate.MODE_NIGHT_NO)
            }
        }
```
效果图 凑合看 虽然很丑 切换前后的 图
<div>
<img src="img/day.jpg" width = "300"/>
<img src="img/night.jpg" width = "300"/>
</div>

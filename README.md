# English Description of EPW_Editor 
After decompressing this program, run the exe file directly to run it.


This program has two functions:

+ Based on the uploaded EPW file, you can export a CSV file that combines the data of the EPW file.

   The data type of EPW contained in its CSV file is as follows:

   + dry_bulb_temperature

   + dew_point_temperature

   + relative_humidity

   +wind_speed

   +wind_direction

   + direct_normal_radiation

   + diffuse_horizontal_radiation

   + global_horizontal_radiation

   + horizontal_infrared_radiation_intensity",

   + direct_normal_illuminance

   + diffuse_horizontal_illuminance

   + global_horizontal_illuminance

   + total_sky_cover

   + atmospheric_station_pressure

   + visibility

   + ceiling_height

   + years

   + monthly_ground_temperature_1

   + monthly_ground_temperature_2

   + monthly_ground_temperature_.....

    


+ Based on the changed CSV file, a new EPW file that conforms to the CSV file data can be generated. *(Note: The EPW file to be changed needs to be uploaded)*

   *Note: CSV cannot change the above data types. Changing meteorological data must comply with the calculation rules of Ladybug model (for details, refer to the source code or instructions of epw model on ladybug tools github).*





# EPW_Editor的中文描述

本程序解压后, 直接运行exe文件即可运行.


本程序有两个功能:

+ 可以基于上传的EPW文件, 导出复合该EPW文件数据的CSV文件.  

  其CSV文件内包含的EPW的数据类型如下:

  + dry_bulb_temperature

  + dew_point_temperature

  + relative_humidity

  + wind_speed

  + wind_direction

  + direct_normal_radiation

  + diffuse_horizontal_radiation

  + global_horizontal_radiation

  + horizontal_infrared_radiation_intensity",

  + direct_normal_illuminance

  + diffuse_horizontal_illuminance

  + global_horizontal_illuminance

  + total_sky_cover

  + atmospheric_station_pressure

  + visibility

  + ceiling_height

  + years

  + monthly_ground_temperature_1

  + monthly_ground_temperature_2

  + monthly_ground_temperature_.....

    


+ 可以基于更改过后的CSV文件, 生成符合CSV文件数据的新的EPW文件. *(注: 需要上传要更改的EPW文件)*

  *注: CSV不可更改上述数据类型. 更改气象数据要符合Ladybug model的计算规则(具体参照ladybug tools github关于epw model的源码或说明).*



本程序参照了Grasshopper的Ladybug Tools插件中Dragonfly的DF creat epw电池的部分代码.



This program refers to part of the code of Dragonfly's DF creat epw battery in Grasshopper's Ladybug Tools plug-in.

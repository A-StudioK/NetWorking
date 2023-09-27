# Configurations | Add dependencies

Opcion 01:

File -> Project Structure -> Dependencies -> app -> + -> 1
(Search and Dowloand)
  - retrofit [com.squareup.retrofit2]
  - converter-gson [com.squareup.retrofit2]
 
↑
↓

Opcion 02:

build.gradle.kts(Module: app) 
dependencies
  - implementation("com.squareup.retrofit2:retrofit:2.9.0")
  - implementation("com.squareup.retrofit2:converter-gson:2.9.0")

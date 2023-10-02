# 甘特圖
```mermaid
gantt
    title A Gantt Diagram

    section Section
    Task1           :a1, 2023-01-01, 1d
    Task2     :a2,after a1  , 4d
    Task3     :a3,after a1  , 17d
    Task4     :a4,after a2  , 70d
    Task5     :a5,after a3  , 10d
    Task6     :a6,after a4  , 30d
    Task7     :a7,after a5  , 25d
    Task8     :a8,after a5  , 20d
    Task9     :a9,after a6  , 25d
    Task10    :a10,after a7 , 20d
    Task11    :a11,after a9 , 25d
```
# PERT圖
![NKUST](Pert.jpg "Pert")

# 關鍵路徑
1->2->4->6->9->11

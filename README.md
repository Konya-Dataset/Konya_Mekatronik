# Konya_Mekatronik# Exploring Diverse Indoor Challenges in Multiple Environments with Konya-Dataset

<table><tbody><tr><td colspan="2"><img src="figures/kutu.jpg"></td></tr><tr><td><img src="figures/asansor.jpg"></td><td><img src="figures/merdiven.jpg"></td></tr></tbody></table>

---

In real world conditions, it is very important for indoor robots to be aware of their environment and react appropriately for robustness and reliability. SLAM algorithms, which play an important role in the navigation of robots, may still localization failure and map distortions in the face of different challenges. In this article, a new indoor dataset called Konya-Dataset is presented to support recent SLAM studies and contribute to data variety with different environments and challenges. This dataset consists of repeated sequences that contain diverse challenges, such as reflective surfaces like mirrors, transitions between floors with elevators or stairs, scene changes over time, illumination conditions and dynamic obstacles, along with common challenging scenarios. It provides opportunities to explore challenges affecting indoor visual and Lidar based systems. The dataset includes 2D Lidar, RGB-D camera, IMU and Leddar sensor data suitable for sensor fusion, collected in environments with different characteristics such as academic buildings, homes and hospitals. Additionally, the dataset contains light sensor data that can be used for awareness of illumination conditions. As a result of the tests, it has been observed that reflective surfaces and transparent surfaces, elevators and stairs, and symmetrical structures that cause incorrect loop closure are still significant challenges for SLAM algorithms. In addition, improvements have been made in SLAM algorithms in the face of difficulties such as illumination changes, dynamic obstacles, and shakes, but we have experienced that sometimes they still cannot cope with these difficulties. Our dataset, which reveals the challenges to focus on and the boundaries of SLAM algorithms, is a critical tool for the community in overcoming the limits.

## Downloads

| Name                                                                                                                                                 | Challenging                                                                | Size (GB) | Duration | Resolution | Laser Projector |
| ---------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | --------- | -------- | ---------- | --------------- |
| [Home1.0](https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EdyoawST075MqUxxJRjFBrgBkQzD4UX28tey7z1PRxaagg?e=kjaGej) | M\*, I\*\*, TR\*\* LL\*\*\*(according to Home1.3,4,5)                      | 11.2      | 145s     | 640x480    | Off             |
| [Home1.1](https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EeE5EFCuhNtIlxL1nsV5LTwBjm_1VGQiixq9tWllblGdiQ?e=9h1AOd) | M\*,I\*\*, TR\*\* LL\*\*\*(according to Home1.3,4,5)                       | 11.6      | 149s     | 640x480    | Off             |
| [Home1.2](https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EZiFjsnHQaZHlisbpns1ZkwBq-_eiTKUaqdH86s8l9GfjA?e=ox64T2) | M\*,I\*\*, F\* TR\*\* LL\*\*\*(according to Home1.3,4,5)                   | 9.3       | 119s     | 640x480    | Off             |
| [Home1.3](https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EfLezyI7rsBJrmu172TNU7cBDckbNZath-ZM-HH_roJnVg?e=MPFlCg) | M\*\*,I\*\*\* F\*\*\*, TR\*\* LL\*\*\*(according to Home1.0,1,2)           | 15,7      | 127s     | 1280x720   | On              |
| [Home1.4](https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EUuEU0hG695GtJexqqYRmY0B15v9GXAoCyQ3Cvb1lF_yRQ?e=KwHUCS) | 4 M\*\*\*\*\*, I\*\*\*\*, F\*\*, TR\*\* LL\*\*\*(according to Home1.0,1,2) | 12.5      | 101s     | 1280x720   | On              |
| [Home1.5](https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EYZhLEsjKBhDu1jwJVelOSIBxpcnuNckBk_eZOjRVGBU_g?e=jQnZGV) | M\*\*\*\*\*,I\*\*\*\*, F\*\*\*, TR\*\* LL\*\*\*(according to Home1.0,1,2)  | 14.9      | 121s     | 1280x720   | On              |

| Name                                                                                                                                                 | Challenging                                                                             | Size (GB) | Duration | Resolution | Laser Projector |
| ---------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | --------- | -------- | ---------- | --------------- |
| [Home2.0](https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EcS8YMhzpf9GpbkWV4P6hxgB1a2nuxeQJq7YFJnbxpbZqQ?e=Bc3VsV) | M\*, I\*\*, D\*, TR\*\* LL\*\*(according to Home2.4,5)                                  | 8.6       | 110s     | 640x480    | Off             |
| [Home2.1](https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EVRf63NZO8BFk1AIOgElUWEBnCeNF_d2T897G6HLX0nZHA?e=rpFbWI) | M\*,I\*\*, TR\*\* LL\*\*(according to Home2.4,5)                                        | 5.1       | 66s      | 640x480    | Off             |
| [Home2.2](https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EQ9X64ylC2pKpmjTeOyelGcBZ828AxVpqnSYcaOS0-DrSw?e=1AqGmi) | M\*\*\*,I\*\*, F\*, VM\*\*\*\* TR\*\*\* LL\*\*(according to Home2.4,5)                  | 15.7      | 202s     | 640x480    | Off             |
| [Home2.3](https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EV4qi9OUheFIiKhezu-JQ0EB1oSTawjv1JV3oEH85gFmVw?e=DOX9Zy) | M\*\*\*\*,I\*\*\*, F\*, VM\*\*\*\*, TR\*\*\* LL\*\*(according to Home2.4,5)             | 9.5       | 123s     | 640x480    | Off             |
| [Home2.4](https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EX5iQHa1MgVCruW8v87qdv4B2yYPHKUveCDr-Mp1Gpi1bg?e=cHCcOd) | M\*\*\*\*\*, I\*\*\*, LL\*\*(according to Home1.0,1,2,3)                                | 10.2      | 82s      | 1280x720   | On              |
| [Home2.5](https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/ETeUUOhO1YpKnsFJu_qL2kkBPM9-OeOLhL474PY9s3a4DQ?e=8fe6fr) | M\*\*\*\*\*,I\*\*\*\*, F\*\*\*, VM\*\*\*\*\*, TR\*\* LL\*\*(according to Home1.0,1,2,3) | 13.2      | 107s     | 1280x720   | On              |

<table><tbody><tr><td>Name</td><td>Challenging</td><td>Size(GB)</td><td>Duration</td><td>Resolution</td><td>Laser Projector</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EazYRJDp-FlCrBWgedhSU1IBizxFhzqqhVjN1A5K2iMj4A?e=XEEv9g">Academic building2.0</a></td><td>M**, I***, F**, D**, TR***</td><td>45.7</td><td>589s</td><td>640x480</td><td>Off</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EQq3V3wxhu5Bsjtq9zrae4QB4lsdQ6Twt9-bOPzRcoH08w?e=K8c36p">Academic building2.1</a></td><td>M***,I****, F**, D*, TR***</td><td>55.3</td><td>713s</td><td>640x480</td><td>Off</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/ETByLggiBzNGgDwrB0VThIoBoICNn4ttjs27evkAiOix0w?e=s1l79H">Academic building2.2</a></td><td>M***,I*****, F**, S*, TR***</td><td>63.1</td><td>814s</td><td>640x480</td><td>Off</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EQ9vC3xvNghLvp788PXTUDEBbmbB-7ibTtxVuG5kZiVb5A?e=hRQASh">Academic building2.3</a></td><td>M*****,I****, F**, D***, TR***</td><td>27.3</td><td>222s</td><td>1280x720</td><td>On</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EQSncZihwcpLg-jbI0vYaWsBeEdPkQuDg-8kssD-d33hHw?e=T4Tn9l">Academic building2.4</a></td><td>M*****, I****, F**, S*, D****, TR***</td><td>35.7</td><td>290s</td><td>1280x720</td><td>On</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EQ52uiHsdrpKpbZXEW2ZLkwB8VFp1VBYpp-j9v1yLM5Sxg?e=taSKrq">Academic building2.5</a></td><td>M****,I****, F*, D****, TR**</td><td>41.4</td><td>337s</td><td>1280x720</td><td>On</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EcxIyuTUo0NJtRgWt9aXIjUBxafvnFVUJ1WGeV3OeBfDeA?e=ujV6L9">Academic building2 ground floor</a></td><td>M**,I****, F**, S****, TR****</td><td>13.6</td><td>226s</td><td>640x480</td><td>Off</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/Ebz_bTzd5bZAiRaPnI285ssB6IQmkNJlurEu7pfZL2T1cg?e=Cz3Ezh">Academic building2 section</a></td><td>M*****,I****, F***, TR*</td><td>14.5</td><td>186s</td><td>640x480</td><td>Off</td></tr></tbody></table>

<table><tbody><tr><td>Name</td><td>Challenging</td><td>Size(GB)</td><td>Duration</td><td>Resolution</td><td>Laser Projector &nbsp; &nbsp; &nbsp;</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/ESJKQxAibehHncWNbOZcvRQBEj1veedPAYqIzKqWHNeqGA?e=R20acd">Home2 mirror0</a></td><td>M**, I***, D*, TR****</td><td>6.2</td><td>80s</td><td>640x480</td><td>Off</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/ET0bI2y115JEpHb0Zz03ZUoBWajPXY4jeo5m1Dqkevs7rQ?e=w5mvhz">Home2 mirror1</a></td><td>M***,I*, TR*****</td><td>3.4</td><td>44s</td><td>640x480</td><td>Off</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/ETiuhjMbELZGm5kouhSqi2kBg0fXUlvfAL0aLy4D-enWuQ?e=p0bVS4">Home2 mirror2</a></td><td>M***,I*, TR*****</td><td>3.3</td><td>42s</td><td>640x480</td><td>Off</td></tr></tbody></table>

<table><tbody><tr><td>Name</td><td>Challenging</td><td>Size(GB)</td><td>Duration</td><td>Resolution</td><td>Laser Projector</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/ES50MZUrOQ9KqmeFXLo764ABGmaM8CJDPPdTYejI5tVk2Q?e=aT7Yde">Academic building1.0</a></td><td>M*, I**, F**, S** TR*</td><td>58.8</td><td>758s</td><td>640x480</td><td>Off</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EQrxRk5PSAZDn5X0vr24tjsBkV1225na1fURVm60H7-QuA?e=eswxFC">Academic building1.1</a></td><td>M**,I*****, F**, S**, TR*</td><td>21.3</td><td>275s</td><td>640x480</td><td>Off</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/ES8x-Eu-FGVEqBTZJ2DXLYkBREXSd1SIsT7bB-X0hhKZ-Q?e=CUBplM">Academic building1.2</a></td><td>M****,I**, F**, S***, TR*</td><td>39.3</td><td>319s</td><td>1280x720</td><td>On</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EYMEf1_Zh9RKmKuuRnTrb_8B_2Ny3OlBtg2sBgIjpJS0fQ?e=fLQj4n">Academic building1.3</a></td><td>M*****,I*****, F**, S***, D***, TR*</td><td>29</td><td>235s</td><td>1280x720</td><td>On</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EXW73FMCMY9Io9y-bxU0ciwBIql5ovtokUARY8mQmVqawQ?e=cEffJ8">Academic building1.4</a></td><td>M**,I***, F**, S**</td><td>17.1</td><td>221s</td><td>640x480</td><td>Off</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EU3t9U4lqZ1PlcOZazrra_8BnLCC172h8oFgF3rW_76sPw?e=RMUAeQ">Academic building1.5</a></td><td>M**,I****, F**, S**, TR*</td><td>18.1</td><td>233s</td><td>640x480</td><td>Off</td></tr></tbody></table>

<table><tbody><tr><td>Name</td><td>Challenging</td><td>Size(GB)</td><td>Duration</td><td>Resolution</td><td>Laser Projector</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EecEHsEGxHBPpaoj3rKAEWABfn8OQSM8ulTTw9vMlWYdcQ?e=wBP8Hj">Academic building3.0</a></td><td>M****, I***, C** TR*****</td><td>23.6</td><td>192s</td><td>1280x720</td><td>On</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EV-nu2UJctxJnJPBYXkbri4BNm52Jza-2e5u_0SlJMH7Eg?e=anWSiL">Academic building3.1</a></td><td>M*****,I*****, C**, TR*****</td><td>15.1</td><td>122s</td><td>1280x720</td><td>On</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EZTMWBoROopCtViZGRwxB5cBX4JlAwe3bbh7nQkB2MsCig?e=9prttV">Hospital1.0</a></td><td>M****, I***, F***, S**, D*****, TR***</td><td>25.1</td><td>204s</td><td>1280x720</td><td>On</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EWrYXluoRW5MvAsqBMoZjIEBsdxX7zsoBlWHGK4EcGc37g?e=bp9GaQ">Hospital1.1</a></td><td>M*****,I***, F**, S**, D*****, TR***, VM****</td><td>27.3</td><td>222s</td><td>1280x720</td><td>On</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EbijUqeXkyVNqeXyJRqWKAEBl6U602_Yldpv7HczCTKcdQ?e=7oOPaf">Store1.0</a></td><td>M****,I*****, F****, S*****, C*****, TR**, VM****</td><td>25.7</td><td>215s</td><td>1280x720</td><td>On</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EUsg8zk3KZhKqkjywJkJdN0B4rHQN5l2bRnZ-cBRbfN5Rw?e=oHWDaa">Market1.0</a></td><td>M*****,I**, S*****, C***, D**</td><td>16.4</td><td>134s</td><td>1280x720</td><td>On</td></tr></tbody></table>

<table><tbody><tr><td>Name</td><td>Challenging</td><td>Size(GB)</td><td>Duration</td><td>Resolution</td><td>Laser Projector</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EQHFrCz0JW1NvIvFIXaYVp0BGrkn_3eUVIf9HQbj5UISXQ?e=JlZFrR">academic_building1_MS0</a></td><td>M**,I*****,C**,TR**,D*,S*****,MS****</td><td>21.8</td><td>281s</td><td>640x480</td><td>Off</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EWPoAnTx0yRNgCsU1ejicx8BxG0D5zCUk3YtjHycr4pQEQ?e=4kLsw5">academic_building1_MS1</a></td><td>M****,I*****,C**,TR**,D*,S***,MS***</td><td>18.9</td><td>244s</td><td>1280x720</td><td>On</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/ERA1RsBD6YxClgch0aUXMowBthZulkGODyAgLevkWX5T2Q?e=amBogf">academic_building1_MS2</a></td><td>M****,I****,C**,TR**,D**,S**,MS****</td><td>31.6</td><td>466s</td><td>1280x720</td><td>On</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EfCPx5jVD8BCgnoi3XKmHScBlBYRdiQBt6iCBxwWeme1pQ?e=u1yQDR">academic_building1_MS3</a></td><td>M****,I****,C**,TR**,D*,S**,MS****</td><td>19.1</td><td>246s</td><td>1280x720</td><td>On</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EURk37gxuI1Ek7SIvmjyAIkBYDuFV3RWyCOQqHiV6CtQfg?e=vIQ4DX">academic_building1_MS4</a></td><td>M*****,I****,C***,TR**,D*,S**,MS*****</td><td>16.8</td><td>216s</td><td>1280x720</td><td>On</td></tr><tr><td><a href="https://erbakanedutr-my.sharepoint.com/:u:/g/personal/mumineyildiz_erbakan_edu_tr/EQ4DtPDmAz1LsjHQ1_L7lHIBduSkvXARrH_s5iaGXOi-yw?e=H3Ng2Q">academic_building1_MS5</a></td><td>M****,I****,C***,TR**,D*,S***,MS****</td><td>17.2</td><td>222s</td><td>1280x720</td><td>On</td></tr></tbody></table>

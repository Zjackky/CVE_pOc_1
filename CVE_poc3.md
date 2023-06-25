# Firmware download

[https://img.baicells.com//Upload/20200804/FILE/6f8fb5e9-8967-4c84-9765-92568e9d4c41.tar](https://img.baicells.com/Upload/20200804/FILE/6f8fb5e9-8967-4c84-9765-92568e9d4c41.tar)



# Code audit



\1.   0x0040ab1c GoaheadSpecifiedSubmitPage



websGetVar receives user parameters and enters the SetLang2Config function. sprintf concatenates into the get_cmd_printf function to execute commands

![image-20230626002033887](C:\Users\Zachariah.Jack\Desktop\tmp_wp_picture\image-20230626002033887.png)



![image-20230626002044210](C:\Users\Zachariah.Jack\Desktop\tmp_wp_picture\image-20230626002044210.png)



# POC

```python
Write in CVE Attack vector(s)
```




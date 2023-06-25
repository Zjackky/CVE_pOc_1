# Firmware download

[https://img.baicells.com//Upload/20200804/FILE/6f8fb5e9-8967-4c84-9765-92568e9d4c41.tar](https://img.baicells.com/Upload/20200804/FILE/6f8fb5e9-8967-4c84-9765-92568e9d4c41.tar)



# Code audit



\1.   0x0040ab1c GoaheadSpecifiedSubmitPage



websGetVar receives user parameters and enters the SetLang2Config function. sprintf concatenates into the get_cmd_printf function to execute commands

![image](https://github.com/Zjackky/CVE_pOc_1/assets/134998334/355d3822-9301-4ee2-8907-903f0be5678e)


![image](https://github.com/Zjackky/CVE_pOc_1/assets/134998334/b23d16d5-0b63-43f4-b157-a8d7a6ab80c0)






# POC

```python
Write in CVE Attack vector(s)
```




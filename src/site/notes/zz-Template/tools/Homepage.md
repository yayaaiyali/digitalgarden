```dataview
>> list from !"zz-Template" and !"yy-Memo" and !"Excalidraw"
>> where date(today) - file.ctime <=dur(7 days)
>> sort file.ctime desc
>> limit 7
>> ```
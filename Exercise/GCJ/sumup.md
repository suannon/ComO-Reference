Sum up !
====================
Tags : `GCJ`<br>
Difficulty #1 : &#9733;&#9733;&#9734;&#9734;&#9734;&#9734;&#9734;&#9734;&#9734;&#9734;<br>
Difficulty #2 : &#9733;&#9733;&#9733;&#9733;&#9734;&#9734;&#9734;&#9734;&#9734;<br>
Estimated time solve : 15 min<br>

- - -

*"โจทย์คลาสสิกนี้สุดจะน่าเบื่อ มีเป็นเบือเห็นแล้วเบื่อโจทย์ง่ายๆ ไม่ลีลาเอาไปทำให้สบาย อ้อระวัง 64 บิต จะไม่พอ"* ... หัวโจทย์ข้อนี้ที่คุณได้อ่านไปทำให้คุณรู้สึกได้ว่ามันกำลังจะใบ้อะไรบางอย่าง ... แต่ช่างเถอะ คุณจึงลงมืออ่านโจทย์ทันที "โจทย์นี้ชื่อว่า Sum up ซึ่งทุกคนก็คงจะเดากันได้ ว่าคือผลรวมของเลข ... เลขสุดคลาสสิกก็คือหาผลรวมของ 1,2,3 ... ไปเรื่อยๆจนถึง N หรือเป็นทางการก็คือ 1+2+3+...+N มีค่าเท่าไหร่ อ้อ แต่คำตอบอาจจะเยอะมากๆ ... ดังนั้นให้นำผลรวมมา mod ด้วย 1000000007 ก่อน แล้วนั่นคือคำตอบของปัญหานี้" เอาล่ะ ได้เวลาลงมือทำสักที ว่าแต่หัวโจทย์นั้นพยายามจะใบ้อะไรน้าา ...

Input
-----
บรรทัดแรกรับจำนวน testcase **T** (**T** <= 10)

แต่ละ testcase รับจำนวนเต็ม 1 ตัว คือ **N**

Output
------
แต่ละ testcase แสดงจำนวนเต็ม 1 ตัว คือคำตอบของ `(1+2+3+...+N) % 1000000007`

Limits
------

Small : 1 <= **N** <= 10000

Large : 1 <= **N** <= 10^18

Example Input
-------
```
5
1
5
10
555
12345678901234567
```

Example Output
-------------
```
1
15
55
154290
344307273
```

Note
----
testcase 1-4 นั้นตาม limit ของ small

testcase 5 นั้นตาม limit ของ large
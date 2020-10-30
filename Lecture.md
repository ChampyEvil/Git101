# พื้นฐาน Command GIT


```sh 
git status
```
`git status` คือ แสดงสถานะไฟล์ที่มีการเปลี่ยนแปลง หรือยังต้องการ add หรือ commit

```sh
git add
```
 คือ การเพิ่มไฟล์เป็นสถานะ stage


```sh
git reset
```
 คือ การ unstage ไฟล์ที่เราเคย stage


```sh
git commit
```
 คือการ commit ไฟล์ที่ stage โดยมักจะใช้  git commit -m เพื่อเพิ่มข้อความในสิ่งที่ทำไป
 
```sh
git log
```
 คือการดูประวัติที่เคย commit ไว้

```sh
git pull
```
 คือการดึงไฟล์จาก remote มายัง local โดยคำสั่ง git pull นั้นจะทำการ git fetch และ git merge ไปด้วย โดยเราจะมักเห็นใช้ git pull -–rebase เพื่อทำการเปลี่ยนฐานแทนการ merge


```sh
git merge (branch)
```
 คือการรวม branch ที่เจาะจงมายัง local


```sh
git fetch
```
 คือ การตรวจสอบไฟล์ภายใน local และ remote ว่าตรงกันหรือไม่


```sh
git push
```
 คือ ส่งการเปลี่ยนแปลงของไฟล์ไปบน remote repository


```sh
git stash
```
 คือ การเก็บซ่อนการเปลี่ยนแปลงทั้งหมดไว้ทั้งหมด และสามารถนำกลับมาโดยใช้ git stash pop


```sh
git checkout (branch)
```
 คือ การเปลี่ยน branch


```sh
git clone (url)
```
 คือการ คัดลอกโปรเจคจาก remote มายัง local
# CTF2018-王紹宇

# Steg-1: STEG(必) 20

# sCTF 2016 Q1 : banana-boy-20

解題步驟1:查看檔案格式
 
 file carter.jpg

解題步驟2:查看檔案內藏的字串

 strings carter.jpg

解題步驟3:查看16進位

 xxd carter.jpg

解題步驟4:binwalk工具

 binwalk carter.jpg

解題步驟5:dd 工具

 dd if=carter.jpg of=carter-1.jpg skip=140147 bs=1

解題步驟6:開啟拉出後的圖片


 =>解答 

exiftool img.jpg


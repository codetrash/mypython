mypython
========

Collection of useful Python scripts

I created the script to resize thousands images in a single-run Python command in Linux (Ubuntu). This will also work in Windows i guess. It can resize thousands of images ( I run it before for > 50K images)

Suppose we have images stored in Folder structures like this : 

images

----  Tigers

-------------1_tigers.jpg

-------------2_tigers.jpg

-------------2_tigers.png

-------------n_tigers.jpg

---- Cats

-------------1_cats.jpg

-------------2_tcats.jpg

-------------2_cats.png

-------------n_cats.jpg

---- n

-------------1_n.jpg

-------------2_n.jpg

-------------3_n.png

-------------n_n.jpg

.............................

ans so on. 

Run the script with this steps : 
================================

1. Open your terminal, and type

2. python resizer.py {img source folder} {the size you want the image to be} {destination folder}

   example : 

       python resizer.py /home/ubuntu/images/ 128 /home/ubuntu/new_images

3. Drink your coffee and watch the terminal running the process 


Notes: 
=============================
1. Install PIL image if you dont have one
2. ANTIALIAS and quality=90 is to prevent the image from downgrading quality 
3. Images will be converted to .jpg extension ( its up to you, you can change it your way)


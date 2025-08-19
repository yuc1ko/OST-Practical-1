# OST-Practical-1
Q1. Create a folder on the desktop

1. cd ~/Desktop

2. mkdir myfolder


Q2. Create nested folder.

1. cd myfolder

2. mkdir nested

Q3. Create a file in sister folder.

1. mkdir sister

2. cd sister

3. touch file1.txt


Q4. Append the data into each folder

1. echo "This is myfolder data" >> ~/Desktop/myfolder/info.txt

2. echo "This is nested folder data" >> ~/Desktop/myfolder/nested/info.txt

3. echo "This is sister folder data" >> ~/Desktop/myfolder/sister/file1.txt

Q5. Rename sister folder into my name

1. cd ~/Desktop/myfolder

2. mv sister spicyuuu

Q6. List the created folders using name

1. ls -R ~/Desktop/myfolder

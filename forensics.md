#### tunn3l_v1s10n

I downloaded the file and ran it on my linux machine
![Screenshot from 2023-11-04 11-23-30](https://github.com/s4twik/picoctf/assets/147993943/0b0af434-00ef-47e1-8bcf-bd61874041e7)
I didn't knew what header file was so i googled it and found out it's the first line of the hex file of the bmp file
so to run the bmp file i had to edit the header file, so i googled what the header file of the bmp file should look like
and accordingly the changes in offset `0A` and `0E` i didn't understand what to do in `0A` so i put it as 0 and `0E` to 40 in hex for which is 0028
![Uploading Screenshot from 2023-11-04 18-58-57.png…]()

i ran the file it worked but i didn't get the password
![Screenshot from 2023-11-04 19-05-49](https://github.com/s4twik/picoctf/assets/147993943/d2382b44-ad96-4d30-8522-3b21204629d3)
i coldn't figure out the problem, then it clicked that the aspect ratio is a bit off
so i googled what offset are meant for the aspect ratio of the file 
i kept changing the height little by little and after a few attempts i got the flag
![Screenshot from 2023-11-04 19-09-32](https://github.com/s4twik/picoctf/assets/147993943/b1ae2f42-53fd-4ecf-b8f8-ee39caca9c4d)
![Screenshot from 2023-11-04 19-09-57](https://github.com/s4twik/picoctf/assets/147993943/09c88b03-0d2a-4d5a-9ad9-245bb005bff9)
![Screenshot from 2023-11-04 18-21-41](https://github.com/s4twik/picoctf/assets/147993943/5ff0aa80-118c-4c22-a224-a880e92b6ae8)

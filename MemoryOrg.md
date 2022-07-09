<img width="1273" alt="image" src="https://user-images.githubusercontent.com/81428296/178093502-2799a8ab-40d7-4290-b8f4-1b002b449cd3.png">

The first column is address which is represented in heximal 

Hence, different below rows in the address column is 16 (note: it is not 10, very misleading)

Also, note that there are 16 dots in the row of each address. Hence, each distinct address correspond to one dot, which is 1 byte, namely 1 character

Also, based the example above and the table below, we can see each bit in the row (no matter address or data) is in deximal, hence corresponds to 4 bits binary data
Hence, 2 bits in deximal here corresponds to 1 byte (8 bits in binary), which is the size of a character (given we need at least 8 bits to represent all characters, i.e., utf-8)
Given each dot corresponds to one address, one character, and thus one byte. It matches what we learn, which is each address store 8 bits data. each instrustion need 4 address and memory is 4 aligned. 
<img width="1484" alt="image" src="https://user-images.githubusercontent.com/81428296/178093530-56607163-dda0-453a-ba85-d23804c19d46.png">

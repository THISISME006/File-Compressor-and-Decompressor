## File-Compressor-Decompressor
This project is based on Huffman Coding, a lossless, bottom-up compression algorithm. It can compress and decompress any text,pdf and jpeg files.


# Implementation in Project
This project supports two functions:

## Encode: 
* Class FileInputStream to opening a connection to an actual file, the file named by the path name {@code name} in the file system.  A new {@code FileDescriptor} object is created to represent this file connection.
* Class FileOutputStream Creates a file output stream to write to the file with the specified name. A new {@code FileDescriptor} object is created to represent this file connection.
* Class GZIPOutputStream Creates a new output stream with the specified buffer size and flush mode.

## Decode: 
Decompresses Huffman coded file passed back to its original file.

# To RUN THIS :
Open cmd in the same folder where your files are stored.
Now type "g++ encode.cpp -o main" , press enter.
Now type "main input.txt Compress.huf" , press enter.
A compressed file with Compress.huf is now creted.
For decoding replace encode.cpp with decode.cpp in step 2 , and intput.txt with Compress.huf.


# Result:
This project is just an implementation of Huffman coding, it is not as efficient as the compression algorithm used currently to compress files.

# Example:
inputFile.txt (2.2MB) is compressed to compressedFile.huf (1.1MB) file and decompressed back to ouputFile.txt (2.2MB).

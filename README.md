## File-Compressor-Decompressor
This project is based on Huffman Coding, a lossless, bottom-up compression algorithm. It can compress and decompress any text,pdf and jpeg files.


# Implementation in Project
This project supports two functions:

## Compressing the file: 
Compressing the file was achieved using the following classes-
*Class FileInputStream to opening a connection to an actual file, the file named by the path name {@code name} in the file system.  A new {@code FileDescriptor} object is created to represent this file connection.

*Class FileOutputStream Creates a file output stream to write to the file with the specified name. A new {@code FileDescriptor} object is created to represent this file connection.

*Class GZIPOutputStream Creates a new output stream with the specified buffer size and flush mode.

## Decompressing the compressed file: 
Decompressing the file was achieved using the following classes-
*Class FileInputStream to opening a connection to an actual file, the file named by the path name {@code name} in the file system.  A new {@code FileDescriptor} object is created to represent this file connection.

*Class GZIPInputStream creates a new input stream with the specified buffer size.

*Class FileOutputStream Creates a file output stream to write to the file with the specified name. A new {@code FileDescriptor} object is created to represent this file connection. 

# GUI of the program :
The GUI of the program uses mainly one Class for the GUI-

*JFrame - this class is a type of container which inherits the java.awt.Frame class. JFrame works like the main window where components like labels, buttons, textfields are added to create a GUI.


# Result:
Successfully implementation of compressing and decompressing of text,pdf and JPEG giles.

# Example:
inputFile.txt (2.2MB) is compressed to compressedFile.huf (1.1MB) file and decompressed back to ouputFile.txt (2.2MB).

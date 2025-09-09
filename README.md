# DATA-COMPRESSION-TOOL
*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SRIBALAJI

*INTERN ID*: CT04DY1002

*DOMAIN*: C PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

The Data Compression Tool is a C program developed to demonstrate the concept of lossless data compression using a simple but effective algorithm called Run-Length Encoding (RLE). In computer science, compression plays a crucial role in reducing the storage space required by files and improving the efficiency of data transmission. This project is designed to implement a basic data compression algorithm in the C language that can both compress and decompress text data. The working principle of the program is straightforward: during compression, it scans the input text character by character, counts consecutive repetitions of the same character, and replaces them with a single instance of the character followed by the number of times it occurs consecutively. For example, an input string such as "aaabbc" would be transformed into "a3b2c1", where the count values indicate how many times each character repeats. This allows the program to represent repeated sequences in a compact form, thereby reducing the size of the text when many repetitions exist. The decompression process then reverses this operation, reading the compressed string and reconstructing the original data by repeating each character according to the stored count. Since no information is lost in this transformation, the algorithm provides lossless compression, ensuring the original file can be perfectly restored from the compressed version. The program is implemented in C, making use of fundamental concepts like arrays, loops, string handling functions, and formatted input-output functions such as printf and scanf. By organizing the solution into separate routines for compression and decompression, the tool remains modular, efficient, and easy to extend. The deliverable of this project is a working tool that can take input directly from the user or from a text file, compress the data using RLE, and also decompress a previously compressed file to verify correctness. Although Run-Length Encoding is most effective on data with long runs of repeated characters—such as simple text files, bitmap images, or binary data—it still serves as an excellent introduction to understanding compression algorithms. While it is not as powerful as advanced methods like Huffman coding, Lempel-Ziv, or arithmetic coding, its simplicity makes it ideal for educational purposes and small-scale applications. This C program not only reinforces core programming skills like string manipulation and control flow but also demonstrates how theoretical concepts of data representation can be applied to solve practical problems. In conclusion, the Data Compression Tool written in C successfully compresses and decompresses text data using the Run-Length Encoding algorithm, serving as both a learning project for beginners and a functional utility for reducing file size in simple cases, while also laying the foundation for exploring more advanced compression techniques in the future.

output:

<img width="1160" height="770" alt="Image" src="https://github.com/user-attachments/assets/0f5c0cea-1036-4e39-af12-79134b887a6f" />

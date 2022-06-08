<!-- Author : Samir Paul -->
<div align="center">
<h1> Text File Compressor De-compressor Web App</h1>
</div>
* This webapp uses Huffman Coding for Text Compression and De-compression.
* Made with JavaScript, HTML5 and CSS3.
* Live Demo: [samirpaul1.github.io/txt-compressor](https://samirpaul1.github.io/txt-compressor/)
             [txt-compressor.herokuapp.com](https://txt-compressor.herokuapp.com/)

## About this application:

* This website performs Lossless data compression and decompression of text(.txt) files using Huffman Algorithm.
* In this algorithm, a variable-length code is assigned to input different characters. The code length is related to how frequently characters are used. Most frequent characters have the smallest codes and longer codes for least frequent characters.
* A Huffman code is a tree, built bottom up, starting with the list of different characters appearing in a text and their frequency. 
* Compression ratio usually improves as the file size increases.
* The website is made responsive (with HTML and CSS ) and interactive (with JavaScript ) .
* An [Info page](https://samirpaul1.github.io/txt-compressor/info.html) is added to give more information about tecnique of **Lossless Data Compression** with Huffman coding.

## User Interface:

- [x] Live Demo
![index](images/readme-images/demo.mp4)

- [x] Upload Your File

![step1](screenshots/step1ss.png)

- [x] Select Action (Compress / De-compress)

![step2](screenshots/step2ss.png)
* Step 3 : Sit Back and Relax
    * Required file gets downloaded automatically when process is complete

    * Compression - Compression Ratio is also displayed 
 
    ![compression](screenshots/compressionss.png)
    * De-compression
 
    ![decompression](screenshots/decompressionss1.png)

* Additional Instructions and Warnings are provided if the above steps are not followed correctly

![noFile](screenshots/noFiless.png)

![smallFile](screenshots/vsmallFiless.png)

* Website is Responsive

![responsive](screenshots/responsivess.png)

* Link at the bottom of the page links to an Info page that provides more information about Huffman Coding

![info1](screenshots/infoss1.png)

![info2](screenshots/infoss2.png)
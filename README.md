## Group 01 Team Members :
# Beam-Java
<table>
  <tr>
   <td align="center"><a href="https://github.com/blonbihani"><img src="https://avatars.githubusercontent.com/blonbihani" width="100px;" alt=""/><br /><sub><b>Bihani Tamang</b></sub></a><br /><a href="https://github.com/blonbihani" title="Code">💻</a></td>
  <td align="center"><a href="https://github.com/GuanMingChee"><img src="https://avatars.githubusercontent.com/GuanMingLee" width="100px;" alt=""/><br /><sub><b>Guan Ming Lee</b></sub></a><br /><a href="https://github.com/GuanMingChee" title="Code">💻</a></td>
  <td align="center"><a href="https://github.com/SpyridonKaperonis"><img src="https://avatars.githubusercontent.com/SpyridonKaperonis" width="100px;" alt=""/><br /><sub><b>Spyridon Kaperonis</b></sub></a><br /><a href="https://github.com/SpyridonKaperonis" title="Code">💻</a></td>
   <td align="center"><a href="https://github.com/soumyarao28"><img src="https://avatars.githubusercontent.com/soumyarao28" width="100px;" alt=""/><br /><sub><b>Soumya Chidambar Rao Waddankeri</b></sub></a><br /><a href="https://github.com/soumyarao28" title="Code">💻</a></td>
  </tr>
</table>
  
## Chee
### Topics covered: [Demo Link](https://use.vg/uQBWKw)
- Installation
- simple word count
## Introduction 
- Beam is an open source, unified model that define and execute both batch and streaming data-parallel processing pipelines. 
- Beam decompose problems into many smaller bundles of data that can be processed independently and in parallel.
- Beam can be used for Extract, Transform, and Load (ETL) tasks and pure data integration.
## Installation Walkthrough
<br/>
1) Download JDK version 8
<br/>
<img src="https://github.com/GuanMingChee/Beam-Java/blob/main/Screenshot%20(4).png">
<br/>
<br/>
2) Set environment variable
<br/>
<img src="https://github.com/GuanMingChee/Beam-Java/blob/main/Screenshot%20(3).png">
<br/>
<br/>
3) Download binary zip archive
<br/>
<img src="https://github.com/GuanMingChee/Beam-Java/blob/main/Screenshot%20(5).png">
<br/>
<br/>
4) Unzip the file, add path of bin directory of apache maven to PATH, check the version with `mvn -v`
<br/>
<img src="https://github.com/GuanMingChee/Beam-Java/blob/main/Screenshot%20(12).png">
<img src="https://github.com/GuanMingChee/Beam-Java/blob/main/Screenshot%20(6).png">
<img src="https://github.com/GuanMingChee/Beam-Java/blob/main/Screenshot%20(13).png">
<br/>
<br/>

## Basic Word Count
<br/>
For Word count, we will need to create a Maven project with all the release/files specified for pipeline use. Then, add the dependency before running the pipeline.
<br/>
1) run the code below with PowerShell
<img src="https://github.com/GuanMingChee/Beam-Java/blob/main/Screenshot%20(13)wc.png">
<br/>
<br/>
2) check the files and pipeline created
<img src="https://github.com/GuanMingChee/Beam-Java/blob/main/Screenshot%20(14)wc.png">
<br/>
<br/>
3) add dependency
<img src="https://github.com/GuanMingChee/Beam-Java/blob/main/Screenshot%20(7).png">
<br/>
<br/>
4) run the word count
<img src="https://github.com/GuanMingChee/Beam-Java/blob/main/Screenshot%20(8).png">
<br/>
After this, you can do "ls counts*" to check the result or go to "word-count-beam" directory and click on they newly generated files.
<br/>
The dataset in .csv files will be map the word to word count. Then, the key value pair will be reduced so that all duplicates will be removed and add to the word count. The whole process is using the dictionary concept in Python. 
<br/>
<br/>

## Soumya Chidambar Rao Waddankeri
### Topics covered: [Demo Link](https://use.vg/uQBWKw)
- Minimal Word Count
## Minimal Word Count
For Minimal Word count, we have created a Maven project with all the release/files specified for pipeline use. Then, add the dependency before running the pipeline and followed the steps mentioned above.

After this, you can do "ls wordcount*" to check the result or go to "word-count-beam" directory and click on they newly generated files.

The dataset in .csv files will be map the word to word count. Then, the key value pair will be reduced so that all duplicates will be removed and add to the word count. The whole process is using the dictionary concept in Java. 
<br/>
<br/>

## Reference
- [Beam](https://beam.apache.org/get-started/quickstart-java/)
- [Apache Maven](https://maven.apache.org/download.cgi)
- [Maven Installation Guide](https://maven.apache.org/install.html)
- [Direct Runner dependency](https://beam.apache.org/documentation/runners/direct/)

## Bihani
### Topics covered:
I will be working on the following tasks on the project:

- Word Count (with a different dataset)

### Dataset:
I will be taking 'HR Analytics: Job change of Data Scientists' dataset which has variety of data about the employee. So, the program will help us count the number of times the words in the dataset are repeated.
<img src = "HR dataset.PNG">
<br>

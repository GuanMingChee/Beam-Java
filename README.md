# Beam-Java
## Chee
### Topics covered: [Demo Link](https://use.vg/uQBWKw)
- installation
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

## Reference
- [Beam](https://beam.apache.org/get-started/quickstart-java/)
- [Apache Maven](https://maven.apache.org/download.cgi)
- [Maven Installation Guide](https://maven.apache.org/install.html)
- [Direct Runner dependency](https://beam.apache.org/documentation/runners/direct/)

# Stream in Node.js

## Idea of this Tutorial
Have you ever run into problems while trying to process huge files in your Node.js application? Large files can overtax your available memory and slow down your workflow to a crawl. Rather than splitting up the files, dealing with multiple errors, or suffering through a time lag, you can try using streams instead.

## Target of this Tutorial
This tutorial will demonstrate how to read, parse, and output large files using Node.js streams.

## Concept of Stream in Node.js
The Node.js stream feature makes it possible to process large data continuously in smaller chunks without keeping it all in memory. 
In other words, you can use streams to read from or write to a source continuously instead of using the traditional method of processing all of it at once.

## Benefit of Stream
- One benefit of using streams is that it saves time, since you don’t have to wait for all the data to load before you start processing. 
- This also makes the process less memory-intensive.

## Where we use Stream?
Some of the use cases of Node.js streams include:

- Reading a file that’s larger than the free memory space, because it’s broken into smaller chunks and processed by streams. 
For example, a browser processes videos from streaming platforms like Netflix in small chunks, making it possible to watch videos immediately without having to download them all at once.
- Reading large log files and writing selected parts directly to another file without downloading the source file. 
For example, you can go through traffic records spanning multiple years to extract the busiest day in a given year and save that data to a new file.

## About this Tutorial
For this tutorial, you’re going to use Node.js streams to process a large CSV file.
Node.js streams are an effective way of handling data in input/output operations. 
In this tutorial, you learned how to read large files with just the source file path, how to parse the streamed data, and how to output the data. 
You’ve seen firsthand how streams can be used to build large-scale, high-performing applications.
Note that using streams in your application can increase its complexity, so be sure that your application really needs this functionality before implementing Node.js streams.
You can use the SaaS cloud-native platform for seamless editing, debugging, deployment, and scaling.

## Install and Run
- Clone this repository.
- Extract zip file(this is big csv source file we will control using Stream)
- Run `npm install` in terminal
- Run `node index`

## Author 
© me 

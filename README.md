# Node.js-File-System-Module

1. this example shows 2 different ways to read and write file: Sync(readFileSync(...)) & Async(readFile(...))

2. at the end of this example shows what callback hell is:

   The reading/opening of <read-this.txt>(data2) depends on the completion of reading <start.txt>(data1),
   The reading/opening of <append.txt>(data2) depends on the completion of reading <read-this.txt>(data3),
   final.txt cannot be written until all reading is complete.

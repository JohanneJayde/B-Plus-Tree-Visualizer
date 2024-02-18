# B-Plus-Tree-Visualizer Using Java Swing
This is a B+ tree visualizer that has been created in Java by Johanne McClenahan
## Background
In Spring 2023, I took Advanced Database Management Systems. During the class, one of the projects required us to create a B+ Tree program that supported inserting, searching for a word, and searching for a range of words. Another key aspect was being able to display the B+ tree to the user. While developing the implementation, it became apparent that testing insertion heavily relied on whether your `printLeavesInSequence` and `printStructureWKeys` methods were working.

This created issues as if you didn't have a proper B+ tree, then printing it wouldn't be helpful. To fix this issue, I want to make a B+ tree visualizer for CSCD 427/527 students. This will allow them to test all methods independently so they have better insight into where their program is breaking.

## End Goal
The end goal for this project is to have a fully working B+ tree visualizer. All a user must do is take their existing files from Project 2 and then drop them in with the visualizer files. The user can then run my program through the command line and then it will open up.

## Features
As of now these are currently planned features.
1. Let the user open the file and enter a URL that they would like to parse. This will replace the command line argument that you must do. It will be using JSOUP.
2. Test the insertion method by showing an interactive model of the program
3. Be able to highlight and search for a word.
4. Show a range search


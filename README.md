# Concurrent Regex
Assignment #2 for the course of Concurrent and Distributed Programming, Unibo.

Design and implement a tool for searching matches of a regexp in a tree or graph structure of files such as a filesystem or a website.

The tool must exhibit the following UI:
Inputs: the base path of the search (e.g., a filesystem path or a webpage URL); properties of the traversal (e.g., max depth).
Outputs: the list of matching files, the % of files with at least one matching, and the mean number of matches among files with matches.
The outputs must be updated in real-time as processing proceeds.

Exercise 1: solve the problem using tasks and executors
Exercise 2: solve the problem using asynchronous programming in the event loop
Exercise 3: complement your solution to use reactive streams

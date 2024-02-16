# CECS 327 Reading Assignment: Processes

### Assignment Description
Answer the following questions from the Chapter 3 reading from your textbook. Be complete with your answers. You may work on these questions with one or two other partners, but *all* students must submit the document individually in their own repositories along with each student's name documented with the submission.

1. Statically associating only a single thread with a lightweight process is not such a good idea. Why not? 

2. Having only a single lightweight process per process is also not such a good idea. Why not? 

3. Describe a simple scheme in which there are as many lightweight processes as there are runnable threads. 

4. Constructing a concurrent server by spawning a process has some advantages and disadvantages compared to multithreaded servers. Discuss a few. 

5. How can we prevent an application from circumventing a window manager, and thus being able to completely mess up a screen? 

6. Is a server that maintains a TCP/IP connection to a client stateful or stateless? Why? 

7. Imagine a Web server that maintains a table in which client IP addresses are mapped to the most recently accessed Web pages. When a client connects to the server, the server looks up the client in its table, and if found, returns the registered page. Is this server stateful or stateless? 

8. Consider a process $P$ that requires access to file $F$ which is locally available on the machine where $P$ is currently running. When $P$ moves to another machine, it still requires access to $F$. If the file-to-machine binding is fixed, how could the systemwide reference to $F$ be implemented? 

9. Describe in detail how TCP packets flow in the case of TCP handoff, along with the information on source and destination addresses in the various headers. 

10. Strong mobility in UNIX systems could be supported by allowing a process to fork a child on a remote machine. Explain how this would work. 

### Deliverables
* Your writeup file *must* be done in [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) format and must be included in the repository as a separate file. View the file [`README.md`](README.md?plain=1) for an example of Markdown.
* Any included images or screenshots should be done in `*.jpg`, `*.png`, or `*.gif` formats, and be included individually as files in your repository (i.e. no binary ‘document’ with the images pasted inside).
* Screenshots or images *may* be linked in your Markdown file writeup if you wish to do so.
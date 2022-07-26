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
Commit the answers to the questions in a readable file to your git repository by the due date and time indicated with your repository. Approved file submission formats are: plain text (\*.txt), Markdown (\*.md), PDF (\*.pdf) or web-renderable HTML (\*.html). Github will look for one of these file formats to confirm your "submission" of the assignment. Other formats will only be accepted with *explicit* approval. **NOTE: \*.docx is *not* acceptable. I will not make exceptions for this rule being violated**.


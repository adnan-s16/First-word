## 📜 The History of "Hello, World!"

The tradition of writing a "Hello, World!" program is the definitive rite of passage for anyone learning to code. It serves as a sanity check to prove that your environment, compiler, and syntax are working properly before moving on to complex logic.

### 1972: The Birth of the Phrase
While small test messages have existed since the dawn of computer science, the specific phrase "hello, world" is widely credited to **Brian Kernighan**, a computer scientist at Bell Laboratories. 

The earliest known iteration appeared in his 1972 internal memorandum, *A Tutorial Introduction to the Language B*. Because the B language limited character constants to four ASCII characters per variable, the phrase had to be split across multiple variables to print out:

```b
main( ) {
  extern a, b, c;
  putchar(a); putchar(b); putchar(c); putchar('! *n');
}
a 'hell';
b 'o, w';
c 'orld';

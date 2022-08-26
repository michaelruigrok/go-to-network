# Go2Network
Go2Network is a revolutionary programming paradigm, compiler and runtime, built on top of Go. It fundamentally refactors the flexibiity, high-availability, development speed, and accessible resource power of software projects to an extent never before seen.

In the Dark Ages of Programming, overbloated, fragile, grotesque were developed at a snail's pace using Monolith architecture,, unaware that the times have changed and nobody wants their lame product anymore. Recently, Microservice architected applications have instantly fixed some of these problems. Go2Network supersedes microservices with something infinitely more agile.

Go2Network is a mesh of nanoservices, which  dynamic form code-as-data-pipeline ecosystem. Any nanoservice can be independently replaced without having to rewrite any other nanoservice, although you can if you want. Each nanoservice is also infinitely scalable, to the point where you can have as many of one nanoservice as you want.

The trick comes in with how well-integrated each Go2Network nanoservice is with each other, while being completely independent. It feels just like you're writing a regular local program, but you're in-fact writing a distributed masterpiece. This is thanks to Go2Network's world-class toolset. Imagine automatically creating a nanoservice configuration for each line inside a code file. You just need to configure the networking and deploy them. And for smaller projects, the `microgo2network` tool can deploy a full Go2Network cluster on a single machine, supporting up to 65535 nanoservices.

This configuration allows for continuous delivery down to the op-code. Everybody knows that most common number of lines of code that cause bugs are just one line. But changing this requires rebuilding the entire application and having to deploy it to a server. With Go2Network, you can update those bugs without having to worry about _any_ other parts of your system. This leads to a development workflow where you don't need to wait months for whole departments to finish developing, you can get apps out when they're fresh. You can push immediate changes to prod, line by line.


The following is an example of a "hello world" nanoservice ecosystem:

nanoservice 1:
```yaml
code:
  - package main
  - func main() {
  -   hello := "Hello"
  -   goToNetwork 'print-hello-world'
  - }
goToNetworks:
     print-hello-world:
        host: 104.22.50.212
        username: hello-world-practice
        password: monkey
```
 
nanoservice  2:
```yaml
code:
- package main
- import "fmt"
- func main() {
-   fmt.Printf("%s World!", hello)
- }

```

Note that `hello` is declared in the first nanoservice, and used in the second. Go2Network automatically transfers program scope in a smart way, meaning that data is only transmitted over the network if it is referenced again. Go2Network will keep track of all the previous nanoservices and resolve data automatically.

Go2Network will be built on-top of the Go programming language, compiler, runtime and online course, since Go has excellent Reactive Programming faculties, but has very procedural-paradigm sensibilities, making it easy for beginners to learn. It has also been used to write many microservice technologies like Docker, Kubernetes and others. Go2Network will share many of the same syntax as Go, but will work very differently.

While Functional Programming is a young Paradigm that has shown to be very good at solving certain issues like Monads, Go2Network will forego functions to rely on the flexibility of procedural style syntax. The Nano Service-as-a-Software architecture will provide enough flexibility for developers to implement their own functional programming constructs on top of the base framework.

As someone who has not used Go or any similar languages, I will be seeking work from experienced programmers to help develop how Go2Network will integrate with Go. So if you have any we would love you to join the Go2Network Foundation™ and help program the future of programming.

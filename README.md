# go-to-network
Go to Network (other allowed stylations are go2network, go to network, and go-to-network) is a revolutionary cluster-computing centric, actor based, event driven programming paradigm, language, compiler and runtime that fundamentally refactors the flexibiity, high-availability and achievable resource usage of software projects to an extent never before seen. It will supersede the microservices architecture with something infinitely more agile, that will shape software architecture for the next century.

Go to Network will be built on-top of the Go programming language, compiler, runtime and online course, since it has excellent Reactive Programming faculties, but has very procedural-paradigm sensibilities, making it easy for beginners to learn. It has also been used to write many microservice technologies like Docker, Kubernetes and others. Go to Network will share many of the same syntax as Go, but will work very differently.

Each Go to Network module runs an individual event nanoservice, which intrinsically operates in tandem with a receiver nanoservice and a sender nano-service to create a code-as-data-pipeline ecosystem. Each nanoservice is infinitely scalable, to the point where you can have as many of one nanoservice as you want.

Unlike microservices, this configuration allows for continuous delivery down to the op-code. Research shows that most common number of lines of code that cause bugs are just one line, but changing this requires rebuilding the entire application and having to deploy it to a server. With Go to Network, you can update those bugs without having to worry about _any_ other parts of your system. 

While Functional Programming is a young Paradigm that has shown to be very good at solving certain issues like Monads, Go to Network will rely on the flexibility of procedural style syntax. The Nano Service as a System will provide enough flexibility for devopers to implement their own functional programming constructs on top of the base framework.

The following is an example of a "hello world" program:

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

Note that `hello` is declared in the first nanoservice, and used in the second. Go to Network automatically transfers program scope in a smart way, meaning that data is only transmitted over the network if it is referenced again. Go to Network will keep track of all the previous nanoservices and resolve data automatically.

Go to Network will also support a world class toolset. Imagine automatically creating a nanoservice configuration for each function or line in a Go to Network file. You just need to configure the networking and deploy them. And for smaller projects, the microgotonetwork tool can deploy a full Go to Network cluster, on a single machine supporting up to 65535 nanoservices.

As someone who has not used Go or any similar languages, I will be seeking work from experienced programmers to help develop how Go to Network will integrate with Go. So if you have any we would love you to join the Go to Network Foundation™ and help program the future of programming.

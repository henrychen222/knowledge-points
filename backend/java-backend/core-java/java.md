
# Reference Documentation
###### Created 10/01/2019
* [tutorials point](https://www.tutorialspoint.com/java/)
* [w3schools](https://www.w3schools.com/java/)
* [how to do in java](https://howtodoinjava.com/java/basics/java-tutorial/)


## String
### string pool
https://www.baeldung.com/java-string-pool
https://www.journaldev.com/797/what-is-java-string-pool
### equal() and hashcode()
https://www.baeldung.com/java-equals-hashcode-contracts
https://dzone.com/articles/working-with-hashcode-and-equals-in-java
https://www.geeksforgeeks.org/equals-hashcode-methods-java/
#### If we override equals(), we must also override hashCode().

## OOP
### Inheritance
https://www.tutorialspoint.com/java/java_inheritance.htm
https://www.w3schools.com/java/java_inheritance.asp
### Polymorphism
https://www.w3schools.com/java/java_polymorphism.asp
https://www.tutorialspoint.com/java/java_polymorphism.htm
https://www.geeksforgeeks.org/polymorphism-in-java/
#### Compile time polymorphism --- overloading
#### Runtime polymorphism ---- overriding
### Encapsulation
https://www.w3schools.com/java/java_encapsulation.asp  (good)
https://www.tutorialspoint.com/java/java_encapsulation.htm
#### sensitive data hidden from user:  private, getter, setter
### Abstraction
https://www.w3schools.com/java/java_abstract.asp
https://www.tutorialspoint.com/java/java_abstraction.htm
### Interface
https://www.w3schools.com/java/java_interface.asp
https://www.tutorialspoint.com/java/java_interfaces.htm
### Overriding and Overloading
https://www.programcreek.com/2009/02/overriding-and-overloading-in-java-with-examples/
### Interface VS Abstract Class
https://www.geeksforgeeks.org/difference-between-abstract-class-and-interface-in-java/
### Difference between final, finally and finalize
https://www.javatpoint.com/difference-between-final-finally-and-finalize
https://www.geeksforgeeks.org/g-fact-24-finalfinally-and-finalize-in-java/
### what is static
https://www.geeksforgeeks.org/static-keyword-java/
https://www.javatpoint.com/static-keyword-in-java

## Collection
https://www.tutorialspoint.com/java/java_collections.htm
* [List](https://docs.oracle.com/javase/7/docs/api/java/util/List.html)
* [ArrayList](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)
* [LinkedList](https://docs.oracle.com/javase/7/docs/api/java/util/LinkedList.html)
* [Vector](https://docs.oracle.com/javase/7/docs/api/java/util/Vector.html)
* [Set](https://docs.oracle.com/javase/7/docs/api/java/util/Set.html)
* [HashSet](https://docs.oracle.com/javase/7/docs/api/java/util/HashSet.html)
* [TreeSet](https://docs.oracle.com/javase/7/docs/api/java/util/TreeSet.html)
* [LinkedHashSet](https://docs.oracle.com/javase/7/docs/api/java/util/LinkedHashSet.html)
* [Map](https://docs.oracle.com/javase/7/docs/api/java/util/Map.html)
* [HashMap](https://docs.oracle.com/javase/7/docs/api/java/util/HashMap.html)
* [TreeMap](https://docs.oracle.com/javase/7/docs/api/java/util/TreeMap.html)
* [LinkedHashMap](https://docs.oracle.com/javase/7/docs/api/java/util/LinkedHashMap.html)

|               | Sorted/Ordered         | Duplicates | null      | synchronized | Memory Allocation                          | Internal           |
|---------------|------------------------|------------|-----------|--------------|--------------------------------------------|--------------------|
| ArrayList     | Insertion order        | Allow      | Allow     | No           | increase 50% size each time                | resizable array    |
| LinkedList    | Insertion order        | Allow      | Allow     | No           |                                            | double linked list |
| Vector        | Insertion order        | Allow      | Allow     | Yes          | increase 100% size each time (double size) |                    |
| HashSet       | No Order               | Not Allow  | Allow     |              |                                            |                    |
| TreeSet       | Sorted,Ascending Order | Not Allow  | Not Allow |              |                                            |                    |
| LinkedHashSet | Insertion order        | Not Allow  | Allow     |              |                                            |                    |

### list vs set
http://net-informations.com/java/cjava/list.htm
#### List is ordered, insertion order, allow duplicates, allow null.
#### Set is not ordered, no duplicates, at most one null
### arraylist vs linkedlist vs vector
https://dzone.com/articles/arraylist-vs-linkedlist-vs
https://stackoverflow.com/questions/40484657/arraylist-linkedlist-and-vector-which-one-is-the-best-for-adding-or-removing-th   
https://medium.com/@gilangkusumajati/arraylist-vs-linkedlist-vs-vector-22e1721a66b0
https://javabeat.net/difference-arraylist-vector-linkedlist-java/
### arraylist vs linkedlist
https://beginnersbook.com/2013/12/difference-between-arraylist-and-linkedlist-in-java/
https://howtodoinjava.com/java/collections/arraylist/linkedlist-vs-arraylist/
https://www.java67.com/2012/12/difference-between-arraylist-vs-LinkedList-java.html
### arraylist vs vector
https://www.geeksforgeeks.org/vector-vs-arraylist-java/
https://www.javatpoint.com/difference-between-arraylist-and-vector
https://javarevisited.blogspot.com/2011/09/difference-vector-vs-arraylist-in-java.html
### hashmap vs treemap vs linkedhashmap
https://stackoverflow.com/questions/2889777/difference-between-hashmap-linkedhashmap-and-treemap
https://www.programcreek.com/2013/03/hashmap-vs-treemap-vs-hashtable-vs-linkedhashmap/
https://dzone.com/articles/hashmap-vs-treemap-vs
https://www.geeksforgeeks.org/differences-treemap-hashmap-linkedhashmap-java/
https://www.tutorialspoint.com/Difference-between-TreeMap-HashMap-and-LinkedHashMap-in-Java
https://www.softwaretestingo.com/hashmap-vs-linkedhashmap-vs-treemap/
https://javarevisited.blogspot.com/2015/08/difference-between-HashMap-vs-TreeMap-vs-LinkedHashMap-Java.html
### check arraylist synchronized
https://www.geeksforgeeks.org/synchronization-arraylist-java/
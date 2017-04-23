# JavaInterviewQuestions
===================================================================
# CoreJAVA:
Difference b/w abstract class and interface?

Explain all oops concepts?

What is marker interface and how many types?

What is Agregation,association and composition?

What is String class in java?

Diff b/w StringBuffer and StringBuilder?

What is serialization in java ?
What is immutable object?
Can you please explain Serializable?
When object de-serialize call so what will happen?
A: it will call default constructor.
B: it will use parametrized that was used earlier for object serilizable/
C:- or else or nothing
Can we define construtor inside interface?
Can we define Variable inside interface?
What is Exception?
How many method in Object class?
Describe wait, notify and Notifyall why it's define in object instead of thread class?
Exception hireachy and types of exception?
Describe features of jdk 1.5,1.6 and 1.7,1.8?
What is difference b/w Method and function?
Describe keyword default,public,private and protected?
What is framework which framework have u used?
What is Agile?
How Many way to create an object in java?
Length of String without using length() method in Java?
How many way to create an object?
What is the difference between creating String as new() and literal?
Count a word in string? e.g:- String s= "This is India” Answer will be :- 3
Find the first non repeated character in a string?
:example:-If the word "stress" is input then it should print 't' as output .
If the word "teeter" is input then it should print 'r' as output .

# Exception:-
1.What is an Exception?
2.What is the purpose of Exception Handling?
3.What is the meaning of Exception Handling?
4.Explain Default Exception Handling Mechanism in java?
5.What is the purpose of try?
6.What is the purpose of catch block?
7. IS Try with multiple catch block is possible?
8.If try with multiple catch block present is order of catch blocks important in which order we have to take?
9.What are various methods to print Exception information? and differentiate them.
10.If an exception raised inside catch block then what will happen?
11. Is it possible to take try, catch inside try block?
12.It possible to take try, catch inside catch block?
13. it possible to take try without catch?
14.What is the purpose of finally block?
15. Is finally block will be execute always?
16. which situation finally block will not executed?
17.If return statement present inside try is finally block will be executed?
18.What is the difference between final, finally and finalize()?
19. it possible to write any statement between try-catch and finally? No
20. it possible to take two finally blocks for the same try?
21.syntax try-finally-catch is valid ?
22.What is the purpose of throw?
23.Is it possible to throw an Error?
24. Is it possible to throw any java object?
25.After throw is it allow to take any statement directly?
26.What is the purpose of throws?
27.What is the difference between throw and throws?
28.What is the difference between throw and thrown?
29. Is it possible to use throws keyword for any java class?
30. If we are taking catch block for an exception but there is no chance of rising that exception in try then what will happen?
31. Explain Exception Handling keyword?
32. Which class act as root for entire java Exception hierarchy?
33. What is the difference between Error and Exception?
34. What is difference between checked exception and unchecked exception?
35. What is difference between partially checked and fully checked Exception?
36. How to create custom Exception?
37. Explain the process of creating the customized Exception.
38.Explain control flow in try, catch, finally.
39. Can you give the most common occurred exception in your previous project.
40. Explain the cases where you used Exception Handling in your previous project?
# Thread:-
Q1. What is Multitasking?
Q2. What is the difference between process-based and Thread-based Multitasking?
Q3. What is Multithreading and explain its application areas?
Q4. What is advantage of Multithreading?
Q5. When compared with C++ what is the advantage in java with respect to Multithreading?
Q6. In how many ways we can define a Thread? Among extending Thread and implementing Runnable which is recommended?
Q7. What is the difference between t.start() and t.run() method?
Q8. Explain about Thread Scheduler?
Q9. If we are not overriding run() method what will happened?
Q10. Is overloading of run() method is possible?
Q11. Is it possible to override start() method?
Q12. we are overriding start() method then what will happen?
Q13. Explain life cycle of a Thread?
Q14.What is the importance of Thread class start() method?
Q15. After starting a Thread if we trying to restart the same thread once again what will happen?
Q16. Explain Thread class constructors?
Q17. How to get and set name of a Thread?
Q18. What is the range of Thread priority in java?
Q19. Who uses Thread priority?
Q20. What is the default priority of the Thread?
Q21. Once we created a new Thread what about its priority?
Q22. How to get and set priority of a Thread?
Q23. If we are trying to set priority of a Thread as 100 what will happen?
Q24. If two threads having same priority then which thread will get chance first for execution?
Q25. If two threads having different priority then which thread will get chance first for execution?
Q26. How we can prevent a thread from execution?
Q27. What is yield() method? Explain its purpose?
Q28. What is purpose of join() method?
Q29. Is join() method is overloaded?
Q30. What is the purpose of sleep() method?
Q31. What is synchronized keyword? Explain its advantages and disadvantages.
Q32. Where we can use synchronized keyword?
Q33. What is object lock? Explain when it is required?
Q34. What is the class level lock? Explain its purpose.
Q35. While a thread executing any synchronized method on the given object is it possible to execute remaining synchronized method of the same object simultaneously by any other thread?
Q36. What is the difference between synchronized method and static synchronized method?
Q37. What is the advantage of synchronized block over synchronized method?
Q38. What is synchronized statement?
Q39. How we can declare synchronized block to get class level lock?
Q40. How two thread will communicate with each other?
Q41. wait(), notify(), notifyAll() method can available in which class?
Q42. Why wait(), notify(), notifyAll() method defines in object class instead of Thread class?
Q43. If a waiting thread got notification then it will entered into which state?
Q44. In which method threads can release the lock?
Q45. Explain wait(), notify(), notifyAll() method uses.
Q46. What is the difference between notify() and notifyAll()?
Q47. Once a Thread got the notification then which waiting thread will get chance?
Q48. How a thread can interrupt another thread?
Q49. What is DeadLock? Is it possible to resolve DeadLock situation?
Q50. Which keyword causes DeadLock situation?
Q51. How we can stop a thread explacitly?
Q52. Explain about suspend() and resume() method?
Q53. What is Starvation()? And Explain the difference between Deadlock and Starvation?

Q54. What is race condition?
Q55. What is Daemon Thread? And give an example?
Q56. What is the purpose of a Daemon Thread?
Q57. How we can check Daemon nature of a Thread?
Q58. Is it possible to change a Daemon nature of a Thread?
Q59. Is main thread is Daemon or non-daemon?
Q60. Once we created a new thread is it daemon or non-daemon.
Q61. After starting a thread is it possible to change Daemon nature?
Q62. When the Daemon thread will be terminated?
Q63. What is green Thread?
Q64. Explain about Thread group?
Q65. What is the Thread Local?
Q66. In your previous project where you used multithreading concept?
# Collection :-
Q1. What are limitations of object Arrays?
Q2. What are differences between arrays and collections?
Q3. what are differences between arrays and ArrayList?
Q4. What are differences between arrays and Vector?
Q5. What is Collection API ?
Q6. What is Collection framework?
Q7. What is difference between Collections and Collection?
Q8. Explain about Collection interface?
Q9. Explain about List interface?
Q10. Explain about Set interface?
Q11. Explain about SortedSet interface?
Q12. Explain about NavigableSet ?
Q13. Explain about Queue interface?
Q14. Explain about Map interface?
Q15. Explain about SortedMap ?
Q16. Explain about NavigableMap?
Q17. Explain about ArrayList class?
Q18. What is RandomAccess Interface?
Q19. Explain about LinkedList class?
Q20. Explain about Vector class?
Q21. What is difference between ArrayList and Vector?
Q22. How we can get synchronized version of ArrayList?
Q23. What is difference between size and capacity of a Collection Object?
Q24. What is difference between ArrayList and Linked List?
Q25. What are legacy classes and interfaces present in Collections framework ?
Q26. what is difference Enumeration and Iterator?
Q27. What are limitations of Enumeration?
Q28. What is difference between enum and Enumeration?
Q29. What is difference between Iterator and ListIterator?
Q30. What is relation between ListIterator and Iterator?
Q31. Explain about HashSet class?
Q32. If we are trying to insert duplicate values in Set what will happen?
Q33. What is LinkedHashSet?
Q34. Differences between HashSet and LinkedHashSet?
Q35. What are major enhancements in 1.4 version of collection frame work?
Q36. Explain about TreeSet?
Q37. What are differences between List and Set interfaces?
Q38. What is Comparable interface?
Q39. What is Comparator interface?
Q40. What are differences between Comparable and Comparator?
Q41. What is difference between HashSet and TreeSet?
Q42. What is Entry interface?
Q43. Explain about HashMap?
Q44. Explain about LinkedHashMap?
Q45. Differences between HashMap and LinkedHashMap ?
Q46. Differences between HashMap and Hashtable?
Q47. What is IdentityHashMap?
Q48. What is difference between HashMap and IdentityHashMap?
Q49. What is WeakHashMap?
Q50. What is difference between HashMap and WeakHashMap?
Q51. What is TreeMap?
Q52. What is Hashtable
Q53. What is PriorityQueue?
Q54. What is Arrays class?
Q55. We are planning to do an indexed search in a list of objects. Which of the two Java collections should you use: ArrayList or LinkedList?
Q56. Why ArrayList is faster than Vector?
# Hibernate:-
1. What is the advantage of Hibernate over JDBC?
2. What is Hibernate?
3. What is ORM ?
4. what does ORM consists of ?
5. What are the ORM levels ?
6. Why do you need ORM tools like hibernate?
7. What Does Hibernate Simplify?
8. What is the main difference between Entity Beans and Hibernate ?
9. What are the Core interfaces and classes of Hibernate framework?
10. What is the general flow of Hibernate communication with RDBMS?
11. What is the need for Hibernate mapping file?
12. What are the important tags of hibernate.cfg.xml?
13. What role does the Session interface play in Hibernate?
14. What role does the SessionFactory interface play in Hibernate?
15. What are the most common ways to specify the Hibernate configuration properties?
16. How do you map Java Objects with Database tables?
17. How do you define sequence generated primary key algorithm in hibernate?
18. What is component mapping in Hibernate?
19. Difference between getCurrentSession() and openSession() in Hibernate ?
20. What are the types of Hibernate instance states ?
21. What are the types of inheritance models in Hibernate?
16. What is Hibernate Query Language (HQL)?
17. What are the ways to express joins in HQL?
18 .Transaction with plain JDBC in Hibernate ?
19 .What are the general considerations or best practices for defining your Hibernate persistent classes?
20 .Difference between session.update() and session.lock() in Hibernate ?
21. What are the Collection types in Hibernate ?
22. What is the difference between sorted and ordered collection in hibernate?
23. What do you mean by Named ñ SQL query?
24. How do you invoke Stored Procedures?
25. Explain Criteria API
26. What is the difference between load() and get()?
27. What is the difference between and merge and update ?
28. Define cascade and inverse option in one-many mapping?
29. Define HibernateTemplate?
30. What are the benefits does HibernateTemplate provide?
31. How do you switch between relational databases without code changes?
32. If you want to see the Hibernate generated SQL statements on console, what should we do?
33. What are derived properties?
34. Define cascade and inverse option in one-many mapping?
35. Explain about transaction file?
36. Difference between session.save() , session.saveOrUpdate() and session.persist()?
37. Explain about the id field?
38. What is the use of dynamic-insert and dynamic-update attributes in a class mapping?
39. What is automatic dirty checking?
40. What are Callback interfaces?
41. What is Hibernate proxy?
42. How can Hibernate be configured to access an instance variable directly and not through a setter method ?
43. How can a whole class be mapped as immutable?
44. Explain about transparent persistence of Hibernate?
45. Explain about the dirty checking feature of Hibernate?
46. What is the effect when a transient mapped object is passed onto a Sessions save?
46. Explain about addClass function?
47. Explain about addjar() and addDirectory() methods?
48. What is lazy fetching in Hibernate? With Example .
49. How to Integrate Struts Spring Hibernate ?
50. How to prevent concurrent update in Hibernate?
51. What is version checking in Hibernate ?
52 . Explain about the dirty checking feature of Hibernate?
53 . What is the effect when a transient mapped object is passed onto a Sessions save?
54 . Explain about addClass function?
# Java 8 :
1 .What are the new feature in java 8 ?
2 . What is functional interface?
3 . Write a Comparator using java 8 ?
4 . What is Optional in java 8 ?
5 . Explain Stream Api. ?
6 .What is Lambda Expression?
7 . What is functional programming.?
8 .What is method reference ?
9 . What are default methods?
10 . Explain reduce function in java 8 ?
11  .Explain what changes are done in Date time api.?
12  . Explain Predicate in java 8 ?
# Agile/Waterfall /Practices :
1. What are the responsibilities of a Scrum master ?
2. What is Product backlog ?
3. Difference between Agile vs Waterfall?
4. Explain Pair programming and its benefit?
5. What is TDD (Test Driven Development)?
6. what is BDD (Behaviour Driven Development)?
7. what is Zero Sprint ?
8. what is spike (POC)?
9. Explain few practices of an agile developer ?(e.g TDD,BDD , Code Refactoring, Continuous delivery,Code Review).
10.What is agile manifesto ? (http://agilemanifesto.org/)
11.Question about code quality and tools ?

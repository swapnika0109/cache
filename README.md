# Cache Service

This project covers a caching functionality.

# Design Considerations:

Few Factors are taken into consideration

i.) Fast Lookups
ii.) Fast removals
iii.) Thread Safe
iv.) Time complexity

For faster lookups and keeping it thread safe, we can utilize hash table.
For faster removals, i consider doubly linked list which would help  

A get operation need to have a O(1) time complexity and similarly,
A put operation needs to have a O(1) time complexity.

Hence for that to happen I considered Hash Table.

So, a hash table would be used for any get or a put operation,
 where as doubly linked list is used when to remove the least recently used (LRU) element from the in memory data.



## Installation

Pre-requisite is Java and Using maven please help to do the below

```

mvn install 

```


## Usage

Import the jar into your pom dependencies

```
			<groupId>com.accessMe</groupId>
			<artifactId>cache</artifactId>
			<version>0.0.1-SNAPSHOT</version>
```



Swagger UI

```
http://localhost:8080/swagger-ui/index.html?configUrl=/v3/api-docs/swagger-config#/
```


## RELEASE
1.0 - Cache Service

## FURTHER RELEASES
1.X 
- Would like to encourage more contributions to this package.

# Related Resources and Integration Testing

## The relations btween Entity classes:

### 1. One-to-Many Relationship

* A **One-to-Many** relationship refers to the relationship between two entities A and B in which one element of A may only be linked to many elements of B, but a member of B is linked to only one element of A.

* A one-to-many relationship between two entities is defined by using the `@OneToMany` annotation in Spring Data JPA.

### 2. One-to-One Relationship

* A **One-to-One** relationship refers to the relationship between two entities tables A and B in which only one element of A may only be linked to one element of B, and vice versa.

* A One-to-One relationship between two entities is defined by using the `@OneToOne` annotation in Spring Data JPA.
 @OneToMany(mappedBy = "library")

    private List<Book> books;

 

    //...

 

}


### 3. Many-to-Many Relationship

* A **Many-to-Many** relationship refers to the relationship between two entities A and B in which one element of A may only be associated with many elements of B and vice versa.

* A Many-to-Many relationship between two entities is defined by using the `@ManyToMany` annotation in Spring Data JPA.
public class Book {

    @Id

    @GeneratedValue

    private long id;

    

    @Column(nullable=false)

    private String title;

    

    @ManyToOne

    @JoinColumn(name="library_id")

    private Library library;

    

    // standard constructor, getter, setter

}

public class Library {

 

    //...
    
### 4. Many-to-One Relationship

* A **Many-To-One** relationship represents a single-valued association where a collection of entities can be associated with the similar entity. Hence, in relational database any more than one row of an entity can refer to the similar rows of another entity.

* A Many-to-One relationship between two entities is defined by using the `@ManyToOne` annotation in Spring Data JPA.





## Integration Testing in Spring

* Spring MVC Test Configuration

Enable Spring in Tests with JUnit 5: 

Enable Spring in Tests with JUnit JUnit 5 defines an extension interface through which classes can integrate with the JUnit test.

We can enable this extension by adding the @ExtendWith annotation to our test classes and specifying the extension class to load. To run the Spring test, we use SpringExtension.class.

We also need the @ContextConfiguration annotation to load the context configuration and bootstrap the context that our test will use.

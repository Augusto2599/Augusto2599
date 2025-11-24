### Hi there, I'm José Augusto! 👋

<br />

<div align="left">
  <img align="right" height="180" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" alt="Coding Animation" />

  ### 👨‍💻 A little about me
  
```java
package com.github.augusto2599;

import java.util.Arrays;
import java.util.List;

public class Augusto {

    private String fullName;
    private String mainOccupation;
    private List<String> technologies;
    private List<String> frameworks;

    public Augusto() {
        this.fullName = "José Augusto";
        this.age = 25;
        this.pronoun = "He/His";
        this.status = "Writing Code ☕";
        this.mainOccupation = "Back-End Developer";
        
        this.technologies = Arrays.asList(
            "Java", "Kotlin", "C++", "SQL"
        );
        
        this.frameworks = Arrays.asList(
            "Spring Boot", "JUnit"
        );
    }
    
    public void sayHello() {
        System.out.println("Welcome to my GitHub profile!");
    }
}

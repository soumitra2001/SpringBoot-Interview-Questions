### 1) What happens if we specify an interface instead of a class in the getBean() method?

**Simple Explanation:**
If you specify an interface, it's like asking Spring, "Give me any object that implements this contract." Spring will find and return an instance of a class that implements that interface.

**Answer to Interviewer:**
"If I specify an interface instead of a class in the `getBean()` method, it's like asking Spring, 'Give me any object that implements this contract.' Spring will find and return an instance of a class that fulfills that interface."

---

### 2) Why do we need a no-arg constructor?

**Simple Explanation:**
A no-arg constructor is like having a default setting in a toy. Spring uses it to create an object without any specific configuration, ensuring it has a starting point.

**Answer to Interviewer:**
"We need a no-arg constructor because it's like having a default setting in a toy. Spring uses it to create an object without any specific configuration, ensuring it has a starting point."

---

### 3) What is Spring Security?

**Simple Explanation:**
Spring Security is like having a bouncer at the entrance of your application party. It manages who can enter, ensuring that only authorized guests get access.

**Answer to Interviewer:**
"Spring Security is like having a bouncer at the entrance of your application party. It manages who can enter, ensuring that only authorized guests get access."

---

### 4) What is component scan?

**Simple Explanation:**
Component scanning is like Spring exploring your house to find all the annotated classes (beans). It's a way for Spring to automatically discover and register beans in your application.

**Answer to Interviewer:**
"Component scanning in Spring is like Spring exploring my house to find all the annotated classes. It's a way for Spring to automatically discover and register beans in my application."

---

### 5) How is component scan done in Spring Boot?

**Simple Explanation:**
In Spring Boot, component scan is like having a smart robot that automatically looks through your entire house (project) without you specifying where to search. It's done by default in the `@SpringBootApplication` annotated class.

**Answer to Interviewer:**
"In Spring Boot, component scan is like having a smart robot that automatically looks through my entire house (project) without me specifying where to search. It's done by default in the `@SpringBootApplication` annotated class."

---

### 6) What is the difference between context:annotation-config and context:component-scan tags?

**Simple Explanation:**
`context:annotation-config` is like turning on the lights, enabling support for annotations. `context:component-scan` is like telling Spring to actively search for and register annotated classes (beans).

**Answer to Interviewer:**
"`context:annotation-config` is like turning on the lights, enabling support for annotations. `context:component-scan` is like telling Spring to actively search for and register annotated classes (beans)."

---

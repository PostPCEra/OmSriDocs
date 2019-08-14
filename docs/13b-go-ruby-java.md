---
id: 13b-go-ruby-java
title: Kotlin(Java), Go & Rails
---
## The next batch of Languages: Kotlin(Java), Go & Rails


https://octoverse.github.com/projects#repositories
 # of Contributors
1	Microsoft/vscode	19K
2	facebook/react-native	10K
3	tensorflow/tensorflow	9.3K
4	angular/angular-cli	8.8K

### Kotlin > Java
Kotlin : mainly for androiod, even for good for regular Java projects as it compiles to JVM byte code and runs in JVM


[Java Vs. Kotlin](https://dzone.com/articles/java-vs-kotlin-which-one-will-be-the-best-in-2019): Which One Will Be the Best in 2019?

Which programming language comes to mind when you hear `Android app development?`

<b>asr:</b> `Lots of love for Kotlin when you read user comment section`

`Guava project`
The [Guava project contains](https://github.com/google/guava/wiki) several of Google's `core libraries that we rely on in our Java-based projects`: collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and so forth. Each of these tools really do get used every day by Googlers, in production services.

asr: `our CodingBot will write Code in Guava and Kotlin not in plain Java, because Java is too verbose for Bot to comprehend.`

10 Reasons Why You Should [Drop Java and Switch to Kotlin](https://moducode.com/blog/10-reasons-java-vs-kotlin/)

```java
private fun checkMonth(i: Int): String {
    return when (i) {
        1 -> "January"
        2 -> "February"
        3 -> "March"
        4 -> "February"
        else -> "Not a valid month"
    }
}

val n = 10
when{
    n in 5..20 -> println("n is in range")
    n > 3 -> println("n is greater than 3")
    n < 5 -> println("n is less than 5")
    else -> n + 5
}

data class Animal(val name: String = "Billy", val age: Int = 1, val noise: String = "Baaaah")
```

```java
// kotlin --------
var students = listOf(Student("John", 0), Student("Julia", 2), Student("Matt", 1),
                Student("Katie", 0), Student("Dan", 0))

var firstList = students.filter { it.mark == 0 }.take(3)
var secondList = students.filter { it.mark == 1 }.take(2)

// java --------
ArrayList<Student> students = new ArrayList<Student>() {{
            add(new Student("John", 0));
            add(new Student("Julia", 2));
            add(new Student("Matt", 1));
            add(new Student("Katie", 0));
            add(new Student("Dan", 0));
}};

ArrayList<Student> firstList = new ArrayList<>();
ArrayList<Student> secondList = new ArrayList<>();

for (Student student: students) {
            boolean isFirstFilled = firstList.size() >= 3;
            boolean isSecondFilled = secondList.size() >= 2;

            if (isFirstFilled && isSecondFilled) break;
            int mark = student.getMark();
            if (mark == 0 && !isFirstFilled) {
                firstList.add(student);
            } else if (mark == 1 && !isSecondFilled) {
                secondList.add(student);
            }
        }
}

```

Kotlin :
Kotlin is the latest statically-typed, open-source programming language that can run effectively on the Java Virtual Machine (JVM). Kotlin is developed by JetBrains and is officially supported by Google.

The recent survey of Jexenter has placed Kotlin as 6th in the top technology trends. To compare Kotlin with Java, we need to understand its benefits and drawbacks. `Business leaders like Pivotal, Atlassian, Pinterest, Evernote, and Uber are now using Kotlin for Android app development.`

As per the [recent statistics by App brain](https://www.appbrain.com/stats/libraries/details/kotlin/kotlin) show the `Kotlin language holding 25.30 percent of market share among the top apps of 2018, with 40.76 percent of installs of the new apps.`




### Android 

- 1. Android [`developer Roadmap for 2019`](https://android.jlelse.eu/android-developer-roadmap-for-2019-14eacb0d0a2)

- 1.1 Setup Android Studio, then Setup Kotlin in Android Studio 
- 1.2 Read Android User interface — Learn more about XML and View components

- 2. `Improving yourself as an Android developer.`
This list will act as more of step by step ladder for you to learn, implement and move forward.

- 2.1 Understand the Activity Lifecycle to push a bug free application
- 2.2 Leverage dynamic and flexible and dynamic UI designs using Fragments
- 2.3 Learn how to debug your Android app — use Android Studio debugger
- 2.4 Master Android activities to build screens that you want a user to navigate through
- 2.5 Gain an understanding of context in Android


- 3. [`7 Third-Party Libraries`](https://android.jlelse.eu/7-third-party-dependencies-every-android-developer-should-know-a751f009ff58) Every Android Developer Should Know: `OkHttp, GSON, Retrofit, Glide, Butter Knife, Crashlytics, Guava`

- 
### GO lang

### Ruby & Rails






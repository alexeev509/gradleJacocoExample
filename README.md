# gradleJacocoExample

This doesn't  work with JDK 15 !!! (I don't know why); But it works with JDK 11,12,13,14;<br /> 

I'm using JDK 14_0_2, Idea community 2020_2_2, gradle 6_8_3;<br />

You must install JDK from oracle site: https://www.oracle.com/ru/java/technologies/javase/jdk14-archive-downloads.html <br />
In Idea: file->project structure->SDK->ADD SDK -> JDK->(path to your jdk 14_0_2)<br />
Install Gradle 6_8_3: https://gradle.org/releases/ <br />
In Idea: file->settings->Build,Execution->Build tools->Gradle->Gradle user home ->(add path to Gradle 6_8_3) <br />

Than you can clone this repository and use command: "gradle test" on Windows; (AND YOU MUST HAVE PATH VARIABLE FOR GRADLE!) <br />
On Linux this command maybe: "./gradlew test" (but i'm not sure) <br />

Or you can run this command "test" with idea user interface (for gradle) <br />


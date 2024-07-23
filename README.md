<h1 align="center">
Hi there <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="40px"> I'm Danilo Aguiar <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> aka Dan <img src="https://user-images.githubusercontent.com/5679180/79618120-0daffb80-80be-11ea-819e-d2b0fa904d07.gif" width="27px">
</h1>

```java
import java.util.List;

public class AboutMe {
    private final String pronouns;
    private final List<String> askMeAbout;
    private final List<String> code;
    private final Technologies technologies;
    private final List<String> currentOccupation;
    private final String challenge;
    private final String goals;
    private final String funFact;

    public AboutMe(String pronouns, List<String> askMeAbout, List<String> code, Technologies technologies, List<String> currentOccupation, String challenge, String goals, String funFact) {
        this.pronouns = pronouns;
        this.askMeAbout = askMeAbout;
        this.code = code;
        this.technologies = technologies;
        this.currentOccupation = currentOccupation;
        this.challenge = challenge;
        this.goals = goals;
        this.funFact = funFact;
    }

    public static record Technologies(
            List<String> frontEndJs, 
            List<String> frontEndCss, 
            List<String> backEndJava, 
            List<String> backEndJs, 
            List<String> backEndPython, 
            List<String> databases, 
            List<String> misc) {
    }

    public static void main(String[] args) {
        Technologies technologies = new Technologies(
                List.of("React", "NextJS"),
                List.of("scss", "styled-components", "Bootstrap"),
                List.of("Spring"),
                List.of("Node", "Express"),
                List.of("flask"),
                List.of("MongoDB", "mySQL", "SQLServer"),
                List.of("Bash", "Selenium")
        );

        AboutMe aboutMe = new AboutMe(
                "he/him",
                List.of("web dev", "tech", "app dev", "photography"),
                List.of("Java", "Python", "Javascript", "Typescript", "HTML", "CSS", "React"),
                technologies,
                List.of("Open for job opportunities"),
                "I’m looking to collaborate with other content creators",
                "Contribute more to Open Source projects",
                "There are two ways to write error-free programs; only the third one works"
        );

        System.out.println("Pronouns: " + aboutMe.pronouns);
        System.out.println("Ask Me About: " + aboutMe.askMeAbout);
        System.out.println("Code: " + aboutMe.code);
        System.out.println("Technologies (FrontEnd JS): " + aboutMe.technologies.frontEndJs());
        System.out.println("Current Occupation: " + aboutMe.currentOccupation);
        System.out.println("Challenge: " + aboutMe.challenge);
        System.out.println("Goals: " + aboutMe.goals);
        System.out.println("Fun Fact: " + aboutMe.funFact);
    }
}


```

<div align="center">
  <a href="https://github.com/cutekitten000">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=cutekitten000&show_icons=true&theme=dracula&include_all_commits=false&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=cutekitten000&layout=compact&langs_count=7&theme=dracula"/>
</div>
<div style="display: inline_block" align="center"><br>
  <img align="center" alt="Dan-Java" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" >
  <img align="center" alt="Dan-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <img align="center" alt="Dan-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Dan-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Dan-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Dan-Ts" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
  <img align="center" alt="Dan-React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
  
  <img align="right" alt="Dan-pic" height="150" style="border-radius:50px;" src="https://github.com/cutekitten001/cutekitten001/blob/cabfb9958b146d4b6ddf8d2256d2769909e41bd7/tumblr_mjso17bD5O1rjcxgso1_400.gif">
</div>
 
 ##
  
 <div>
   
<section align="center">
----
</section>
   
  ![Snake animation](https://github.com/cutekitten001/cutekitten001/blob/cabfb9958b146d4b6ddf8d2256d2769909e41bd7/github-contribution-grid-snake.svg) 
 
 </div>

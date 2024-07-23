<h1 align="center">
Hi there <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="40px"> I'm Danilo Aguiar <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> aka Dan <img src="https://user-images.githubusercontent.com/5679180/79618120-0daffb80-80be-11ea-819e-d2b0fa904d07.gif" width="27px">
</h1>
<h3 align="center">A passionate Java backend developer from Brazil</h3>

---
```java
import java.util.List;

/**
 * This class represents information about me, Dan.
 */
public class AboutMe {
    private final String pronouns;
    private final List<String> askMeAbout;
    private final List<String> code;
    private final Technologies technologies;
    private final List<String> currentOccupation;
    private final String challenge;
    private final String goals;
    private final String funFact;

    /**
     * Constructor to initialize the AboutMe object with my details.
     *
     * @param pronouns           my pronouns
     * @param askMeAbout         topics to ask me about
     * @param code               programming languages I know
     * @param technologies       technologies I am familiar with
     * @param currentOccupation  my current occupation
     * @param challenge          current challenge I am working on
     * @param goals              my goals
     * @param funFact            a fun fact about me
     */
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

    /**
     * This record represents various technologies I am familiar with.
     */
    public static record Technologies(
            List<String> frontEndJs, 
            List<String> frontEndCss, 
            List<String> backEndJava, 
            List<String> backEndJs, 
            List<String> backEndPython, 
            List<String> databases, 
            List<String> misc) {
    }

    /**
     * Main method to demonstrate the creation of the AboutMe object with my details.
     *
     * @param args command line arguments
     */
    public static void main(String[] args) {
        // Initializing the Technologies object with technologies I am familiar with.
        Technologies technologies = new Technologies(
                List.of("React", "NextJS"),                       // Frontend JavaScript frameworks
                List.of("scss", "styled-components", "Bootstrap"), // Frontend CSS frameworks
                List.of("Spring"),                                 // Backend Java frameworks
                List.of("Node", "Express"),                        // Backend JavaScript frameworks
                List.of("flask"),                                  // Backend Python frameworks
                List.of("MongoDB", "mySQL", "SQLServer"),          // Databases I have worked with
                List.of("Bash", "Selenium")                        // Miscellaneous technologies
        );

        // Creating an instance of AboutMe with my personal details.
        AboutMe aboutMe = new AboutMe(
                "he/him", // My pronouns
                List.of("web dev", "tech", "app dev", "photography"), // Topics to ask me about
                List.of("Java", "Python", "JavaScript", "TypeScript", "HTML", "CSS", "React"), // Programming languages I know
                technologies, // Technologies I am familiar with
                List.of("Open for job opportunities"), // My current occupation status
                "I’m looking to collaborate with other content creators", // My current challenge
                "Contribute more to Open Source projects", // My goals
                "There are two ways to write error-free programs; only the third one works" // A fun fact about me
        );

        // Printing my details to the console
        System.out.println("Pronouns: " + aboutMe.pronouns);
        System.out.println("Ask Me About: " + aboutMe.askMeAbout);
        System.out.println("Code: " + aboutMe.code);
        System.out.println("Technologies (Frontend JS): " + aboutMe.technologies.frontEndJs());
        System.out.println("Technologies (Frontend CSS): " + aboutMe.technologies.frontEndCss());
        System.out.println("Technologies (Backend Java): " + aboutMe.technologies.backEndJava());
        System.out.println("Technologies (Backend JS): " + aboutMe.technologies.backEndJs());
        System.out.println("Technologies (Backend Python): " + aboutMe.technologies.backEndPython());
        System.out.println("Technologies (Databases): " + aboutMe.technologies.databases());
        System.out.println("Technologies (Misc): " + aboutMe.technologies.misc());
        System.out.println("Current Occupation: " + aboutMe.currentOccupation);
        System.out.println("Challenge: " + aboutMe.challenge);
        System.out.println("Goals: " + aboutMe.goals);
        System.out.println("Fun Fact: " + aboutMe.funFact);
    }
}


```
---
<h3 align="center">Languages and Tools:</h3>
<div style="display: inline_block" align="center"><br>
  <img align="center" alt="Dan-Java" height="70" width="70" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" >
  <img align="center" alt="Dan-Python" height="70" width="70" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">  
  <img align="center" alt="Dan-Node" height="70" width="70" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-plain-wordmark.svg" />
  <img align="center" alt="Dan-Js" height="70" width="70" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Dan-Ts" height="70" width="70" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
  <img align="center" alt="Dan-React" height="70" width="70" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">

  <img align="right" alt="Dan-pic" height="150" style="border-radius:50px;" src="https://github.com/cutekitten001/cutekitten001/blob/cabfb9958b146d4b6ddf8d2256d2769909e41bd7/tumblr_mjso17bD5O1rjcxgso1_400.gif">
</div>

---
<div align="center">
  <a href="https://github.com/cutekitten000">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=cutekitten000&show_icons=true&theme=dracula&include_all_commits=false&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=cutekitten000&layout=compact&langs_count=7&theme=dracula"/>
</div>

 
 ##
  
 <div>
   
  ![Snake animation](https://github.com/cutekitten001/cutekitten001/blob/cabfb9958b146d4b6ddf8d2256d2769909e41bd7/github-contribution-grid-snake.svg) 
 
 </div>

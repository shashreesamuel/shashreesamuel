<h1 align="center">Hi 👋, I'm TheCoderGuru</h1>

<h4 align="center">I like to code in innovative ways</h4>

<br>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=thecoderguru" alt="thecoderguru" /></a> </p>

<img align="right" height="274px" width="364px" src="https://cdn.dribbble.com/users/1025838/screenshots/6220885/devguy3.gif">

<br>

<h3>Biography</h3>

Lets rewind to where it all began... 2019. I never knew what programming was or how to start programming until I watched a youtube tutorial where a teenager was explaining intricate programming concepts. This intrigued me so much that I decided to experiment on my own and thus I did a Javascript course on Codecademy which taught me the fundamentals of Javascript. From that point onwards, programming was continuous in my life and while my knowledge of programming is quite small, I thoroughly enjoy programming and having fun learning new programming concepts everyday. In addition I am a passionate UX Designer as my hobby hence I try to design captivating websites with the hope to change the aspect of how websites should look like in the future. <br> I believe that learning should be enjoyable and not stressful :smile:

<br>

Follow me on Social Media

[Behance](https://www.behance.net/shashreesamuel2003)

[Instagram](https://www.instagram.com/thecoderguru_official)



<br>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=thecoderguru&show_icons=true&locale=en&layout=10" alt="thecoderguru" /></p>

<img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TheCoderGuru&layout=compact" alt="thecoderguru" />


<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=thecoderguru&" alt="thecoderguru" /></p>

```java

public class TheCoderGuru{

  String firstName;
  String lastName;
  String[] hobbies;
  String[] programming_languages;
  
  
  public TheCoderGuru(String firstName, String lastName, String[] programming_languages, String[] hobbies ){
    
    this.firstName = firstName;
    
    this.lastName = lastName;
    
    this.programming_languages = programming_languages;
    
    this.hobbies = hobbies;
  
  }    

  
  public void setfirstName( String firstName ){
    
    this.firstName = firstName;
  
  }

  
  public void setlastName( String lastName ){
    
    this.lastName = lastName;
  
  }


  public void setProgrammingLanguages( String[] programming_languages ){
    
    this.programming_languages = programming_languages;
  
  }
  
  
  public void setHobbies( String[] hobbies ){
    
    this.hobbies = hobbies;
  
  }


  public String getfirstName(){
    
    return firstName;
  
  }


  public String getlastName(){
   
   return lastName;
  
  }
  
  
  public String getProgrammingLanguages(){
   
   return programming_languages;
  
  }
  
  
  public String[] getHobbies(){
    
    return hobbies;
  
  }

  
  public static void main( String[] args ){
    
    String[] programming_languages = new String[]{ 
    
      "Java", 
      
      "Ruby", 
      
      "Python", 
      
      "C++", 
      
      "SQL" 
      
    };
    
    String[] hobbies = new String[]{
    
      "Playing with my pet"
      
      "Designing Websites"
      
      "Coding",
      
      "Watching rainfall",
    
    }
    
    Array thecoderguru = new TheCoderGuru( "Shashree", "Samuel", programming_languages, hobbies );
    
    System.out.println( thecoderguru.hobbies[0] );
    
  }

}

```

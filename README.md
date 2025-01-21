<h2 align="center">Hey there <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"> , I'm <a href="https://triggeercat.github.io/profile/">TriggeerCat</a></h2>
<p align="center">
  • <a href="https://t.me/triggeercat">My telegram</a> •
</p>

<img align="right" top="500" height="270" width="400" alt="GIF" src="https://github.com/SophieNguyen113/SophieNguyen113/blob/main/Sophie%20Nguyen%20-%20CatCat.gif">

### About Personal Stuffs:

- 👨🏽‍💻  My skills (currently in development): HTML / CSS.
- 🥝  I'm amateur translator into Ukrainian for fun.
- 🌱  I’m currently learning Javascript.
- 🐈‍⬛  Meow
- 💬  Ask me anything, I am happy to help.
- 📫  How to reach me: zspwdmnplay@gmail.com.

<br>

### My github stats, because why not
![GitHub stats](https://github-readme-stats.vercel.app/api?username=TriggeerCat&theme=transparent&show_icons=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=TriggeerCat&layout=compact&theme=transparent)
<br>
*NOTE: These do not indicate my skill level or something like that, it's a github metric which I put in just because I'm interested in tracking my progress*

<br>

### What if my life was a java code
 ```Java
class Developer
{
    String name;
    boolean isInFrontOfTheComputer;
    int energyLevel;

    public Developer(String name)
    {
        this.name = name;
        this.isInFrontOfTheComputer = true; // Starts in front of the computer
        this.energyLevel = 100; // Full energy to start
    }

    public void code()
    {
        System.out.println(name + " is writing brilliant code!");
        energyLevel -= 10; // Coding consumes energy
    }

    public void takeABreak()
    {
        System.out.println(name + " is taking a break to recharge.");
        energyLevel += 20; // Breaks restore energy
        if (energyLevel > 100) energyLevel = 100; // Max energy cap
    }

    public void crash()
    {
        System.out.println(name + " has fallen asleep at the keyboard... Zzz...");
        isInFrontOfTheComputer = false;
    }

    public boolean isInFrontOfTheComputer()
    {
        return isInFrontOfTheComputer;
    }
}

public class DeveloperLife
{
    public static void main(String[] args)
    {
        Developer dev = new Developer("TriggeerCat");

        while (dev.isInFrontOfTheComputer())
        {
            dev.code();
            if (dev.energyLevel <= 30)
            {
                 dev.takeABreak();
            }

            if (dev.energyLevel <= 0)
            {
                dev.crash();
            }

            try
            {
                Thread.sleep(1000); // Simulates time passing
            } catch (InterruptedException e)
            {
                System.out.println("Something interrupted the developer!");
            }
        }

        System.out.println("The coding session has ended. Goodbye, " + dev.name + "!");
    }
}
 ```

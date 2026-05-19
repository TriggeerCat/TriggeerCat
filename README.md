<h2 align="center">Hey there <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"> , I'm TriggeerCat</h2>
<p align="center">
  • <a href="https://t.me/triggeercat">My telegram</a> •
</p>

<img align="right" top="500" height="270" width="400" alt="GIF" src="https://github.com/SophieNguyen113/SophieNguyen113/blob/main/Sophie%20Nguyen%20-%20CatCat.gif">

### About Personal Stuffs:

- 👨🏽‍💻  My skills (currently in development): HTML / CSS / JS (and TS) / React / NodeJS.
- 🥝  I'm amateur translator into Ukrainian for fun.
- 🌱  I’m currently experimenting with new JavaScript libraries.
- 🐈‍⬛  Meow.
- 📫  How to reach me: zspwdmnplay@gmail.com.

<br>

### What if my life was in typescript
 ```Typescript
class Developer {
    private readonly name: string;
    private isInFrontOfTheComputer: boolean;
    private energyLevel: number;

    public constructor(name: string) {
        this.name = name;
        this.isInFrontOfTheComputer = true; // Starts in front of the computer
        this.energyLevel = 100; // Starts with full energy
    }

    public code() {
        console.log(this.name + " is writing brilliant code!");
        this.energyLevel -= 10; // Coding consumes energy
    }

    public takeABreak() {
        console.log(this.name + " is taking a break to recharge.");
        this.energyLevel += 20; // Breaks restore energy
        if (this.energyLevel > 100) this.energyLevel = 100; // Max energy cap
    }

    public crash() {
        console.log(this.name + " has fallen asleep at the keyboard... Zzz...");
        this.isInFrontOfTheComputer = false;
    }

    public getName() {
        return this.name;
    }

    public getEnergyLevel() {
        return this.energyLevel;
    }

    public getFrontOfTheComputer() {
        return this.isInFrontOfTheComputer;
    }
}

const DevelopersLife = async () => {
    const dev: Developer = new Developer("TriggeerCat");

    while (dev.getFrontOfTheComputer()) {
        dev.code();
        if (dev.getEnergyLevel() <= 30) {
            dev.takeABreak();
        }

        if (dev.getEnergyLevel() <= 0) {
            dev.crash();
        }

        try {
            await new Promise((resolve) => setTimeout(resolve, 1000));
        } catch {
            console.log("Something interrupted the developer!");
        }
    }

    console.log("The coding session has ended. Goodbye, " + dev.getName() + "!");
}

DevelopersLife().then();
 ```

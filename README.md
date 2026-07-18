Hi my name is `Antoni Wojcieszyk` also known online as `Jason.json`.

I mostly work with my private repositories and I am a huge fan of low level programming languages such as [C](https://en.wikipedia.org/wiki/C_(programming_language)) and [Rust](https://rust-lang.org/).

I've made and maintain [lisia-nora.net](https://lisia-nora.net). I like to work with [GO](https://go.dev/) and [Rust](https://rust-lang.org/) and I really think that both of them has sommething unique about them.
My first language which I used like 8-10 years ago was [C#](https://en.wikipedia.org/wiki/C_Sharp_(programming_language)), but I am not a huge fan of it. I love strict compiled languages. I've read a lot of books and my I want to improve my skills in [C](https://en.wikipedia.org/wiki/C_(programming_language)) and [C++](https://en.wikipedia.org/wiki/C%2B%2B).

## The tech stack I like to work with:

### Languages (in order of most used):
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)![GDScript](https://img.shields.io/badge/GDScript-%2374267B.svg?style=for-the-badge&logo=godotengine&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)


### Frameworks / libraries:

![SolidJS](https://img.shields.io/badge/SolidJS-2c4f7c?style=for-the-badge&logo=solid&logoColor=c8c9cb)![Tauri](https://img.shields.io/badge/tauri-%2324C8DB.svg?style=for-the-badge&logo=tauri&logoColor=%23FFFFFF)![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white)![Godot Engine](https://img.shields.io/badge/GODOT-%23FFFFFF.svg?style=for-the-badge&logo=godot-engine)

### Runtime:
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)![Flatpak](https://img.shields.io/badge/flatpak-%234A90D9.svg?style=for-the-badge&logo=flatpak&logoColor=white)![FreeBSD](https://img.shields.io/badge/-FreeBSD-%23870000?style=for-the-badge&logo=freebsd&logoColor=white)![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)![Alpine Linux](https://img.shields.io/badge/Alpine_Linux-%230D597F.svg?style=for-the-badge&logo=alpine-linux&logoColor=white)![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

### Databases:

![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)

### CLI:
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)![PNPM](https://img.shields.io/badge/pnpm-%234a4a4a.svg?style=for-the-badge&logo=pnpm&logoColor=f69220)![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)![tmux](https://img.shields.io/badge/tmux-%23000000?style=for-the-badge&logo=tmux&logoColor=%231BB91F)![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

### Web Styling:
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)


"An idiot admires complexity, a genius admires simplicity." ~ Rest in peace King Terry

<div align="center">
 <img src="https://github.com/user-attachments/assets/9df7b607-5ddc-41fe-bc01-d2875cd97c57" alt="dancing terry davis"/>
</div>

#### A simple mocked renderer concept

```rs
use holylibrary::{HolySprite, HolyDraw};

#[derive(HolySprite)]
struct TerryDavis<'a> {
    sprite_source: &'a str,
}

fn main() {
    let terry = TerryDavis {
        sprite_source: "dacing-terry.gif",
    };
    
    // (x, y, z-index)
    let positions = vec![
        (50, 50, 3),
        (150, 50, 3),
        (250, 50, 3),
        (350, 50, 3),
        (450, 50, 1),
    ];
    
    loop {
      holylibrary::refresh_screen();

      for (x, y, z) in positions {
        terry.draw_at(x, y, z);
      }
 
     holylibrary::sleep_ms(16);
    }
}
```

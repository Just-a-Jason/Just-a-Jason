Hi my name is Jason.json.

I mostly work with my private repositries and I am a huge fan of low level programming languages and also a huge fan of Rust. When I was younger I always wanted to code things wich help and bring happiness to people around me. 

I am a second owner of [lisia-nora.pl](https://lisia-nora.pl). 

I love "The Sopranos" and my family.

## Technology I like to use:
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)![GDScript](https://img.shields.io/badge/GDScript-%2374267B.svg?style=for-the-badge&logo=godotengine&logoColor=white)![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)![SolidJS](https://img.shields.io/badge/SolidJS-2c4f7c?style=for-the-badge&logo=solid&logoColor=c8c9cb)![Tauri](https://img.shields.io/badge/tauri-%2324C8DB.svg?style=for-the-badge&logo=tauri&logoColor=%23FFFFFF)![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)![PNPM](https://img.shields.io/badge/pnpm-%234a4a4a.svg?style=for-the-badge&logo=pnpm&logoColor=f69220)![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white)


"An idiot admires complexity, a genius admires simplicity." - Rest in peace King Terry

<div align="center">
 <img src="https://github.com/user-attachments/assets/9df7b607-5ddc-41fe-bc01-d2875cd97c57" alt="dancing terry davis"/>
</div>

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

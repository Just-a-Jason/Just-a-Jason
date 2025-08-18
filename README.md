Hi my name is Jason.json.

I mostly work with my private repositries and I am a huge fan of low level programming languages and also a huge fan of Rust. When I was younger I always wanted to code things wich help and bring happiness to people around me. 

I am a secound owner of [https://lisia-nora.pl](lisia-nora.pl). 

I love "The Sopranos" and my family.

## Technology I like to use:
<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" height="40" alt="rust logo"  />
  
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript-logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img src="https://cdn.simpleicons.org/php/php-oryginal.svg" height="40" alt="php logo"  />
   <img src="https://cdn.simpleicons.org/c" height="40" alt="tailwindcss logo"  />
  <img src="https://cdn.simpleicons.org/tailwindcss/06B6D4" height="40" alt="tailwindcss logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/solidjs/solidjs-original.svg" height="40" alt="solidjs logo"  />
 
  
  <img src="https://cdn.simpleicons.org/docker/2496ED" height="40" alt="docker logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="40" alt="linux logo"  />
</div>
<br/>

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

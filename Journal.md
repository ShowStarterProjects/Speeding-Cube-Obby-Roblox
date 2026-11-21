# Journal
### A journal for the reviewers about the development process of the game
---

## 20/11/2026  
Entry 1  
Found out about journal.md from stelle lol

Until now, most of the stuff had been building and modelling of the first 6-7 stages

<img width="1322" height="562" alt="image" src="https://github.com/user-attachments/assets/f03b87d5-0419-4796-b1a5-5a8ecb5f72c9" />

### Checkpoint system

<img width="322" height="219" alt="image" src="https://github.com/user-attachments/assets/4b952395-c9c3-47f8-8c61-7fef02f6633b" />
<img width="322" height="219" alt="image" src="https://github.com/user-attachments/assets/b9f528b0-02f9-4e28-9635-a5fe9ce1fe09" />

This one took a lot of time, and most of it went into the dumbest bug fixing :sob:...  
The system is in localscript, it stores ur currentCheckpoint ofc, but it also changes your skybox to match the stage theme.  
When you touch a new checkpoint, it plays a ding sound, changes the checkpoint material from neon to plastic and disables the particles.  


### Stage 2: Clouds and Rainbows

<img width="680" height="484" alt="image" src="https://github.com/user-attachments/assets/c28249f2-93a8-4228-ada9-09531f48457b" />

A localscript makes the cloud/rainbow transparent in about 2 seconds when player jumps on it, turns CanCollide false at transparency 1, and in 4 seconds, the platform comes back.

### Stage 4: Binary hacker stage ouu

<img width="842" height="534" alt="image" src="https://github.com/user-attachments/assets/7e8149b8-089b-4561-929f-327d294dd702" />

The red parts are killbricks, touching them kills u, it has a debounce too.

### Hackatime hours: 2h 46m
---

## 22/11/2026
Entry 2
Small Progress/updates, no new stages  

### Re-done Stage 4: Ouuu binary flashing hackerr stage  

<img width="838" height="332" alt="image" src="https://github.com/user-attachments/assets/f69fcb81-d23a-4621-8dd3-c170eb31a919" />

The platforms are now divided into 2 groups, they alternatively become intangible and gray

### Re-done Stage 3: Planet leaps

<img width="783" height="453" alt="image" src="https://github.com/user-attachments/assets/30d1b065-347f-4e53-9448-3c7030876787" />

Instead of boring normal jumps, your gravity becomes lower for the stage and then reverts once u move to the next stage

### New feature to Stage 6: Furniture

<img width="820" height="507" alt="image" src="https://github.com/user-attachments/assets/5f35fcd9-d7cd-43eb-aa59-be276ca98378" />

One of these pieces of furniture isnt very stable, it may fall

### New feature to Stage 7: Crossy Highway

<img width="915" height="549" alt="image" src="https://github.com/user-attachments/assets/e23cd7d7-592b-4e81-82f1-6a334d355f9b" />

Theres an oil spill which makes u trip over for a few seconds, jumping over the cars is a smarter move

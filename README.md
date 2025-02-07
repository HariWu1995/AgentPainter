# AI Agent as a Painter

<div>
  <img src="./assets/poster.png" width="800">
</div>

## Abstract

- To teach AI to draw any painting like human, who can use a small number of strokes to create masterpiece paintings.

- With the support of a **neural
renderer**, the agent can learn to:
    - determine the **position** and **color** of each stroke;
    - make **long-term plan** to decompose texture-rich images into sequence of strokes. 

- Experiments demonstrate that
masterpiece visual quality can be achieved using only hundreds of strokes. 

- The training process does not require any ~~supervised data~~. 

## Demo

![Input](./samples/monalisa.png) ![Result](./results/monalisa.gif)

<details>
    <summary>More samples</summary>
    <img src="./results/sunrise.gif">
    <img src="./results/sunflower.gif">
    <img src="./results/palacemuseum.gif">
    <img src="./results/deepdream_night.gif">
    <img src="./results/deepdream_bird.gif">
</details>

## Model Weights

Remember to rename the checkpoints to **renderer.pkl** and **actor.pkl**

- **default** stroke: [renderer.pkl](https://drive.google.com/open?id=1-7dVdjCIZIxh8hHJnGTK-RA1-jL1tor4) and [actor.pkl](https://drive.google.com/open?id=1a3vpKgjCVXHON4P7wodqhCgCMPgg1KeR)

- **triangle** stroke: [renderer.pkl](https://drive.google.com/open?id=1YefdnTuKlvowCCo1zxHTwVJ2GlBme_eE) and [actor.pkl](https://drive.google.com/open?id=1k8cgh3tF7hKFk-IOZrgsUwlTVE3CbcPF)

- **circle** stroke: [renderer.pkl](https://drive.google.com/open?id=1kI4yXQ7IrNTfjFs2VL7IBBL_JJwkW6rl) and [actor.pkl](https://drive.google.com/open?id=1ewDErUhPeGsEcH8E5a2QAcUBECeaUTZe)

- **curve** stroke: [renderer.pkl](https://drive.google.com/open?id=1XUdti00mPRh1-1iU66Uqg4qyMKk4OL19) and [actor.pkl](https://drive.google.com/open?id=1VBtesw2rHmYu2AeJ22XvTCuzuqkY8hZh)

## Features in Future

✅ Simple GUI

⬜ Motion Path with Drawing Hand [ppt](https://youtu.be/QQyag99u1sk) 

## Reference



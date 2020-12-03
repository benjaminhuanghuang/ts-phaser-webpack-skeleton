
Game
```
import "phaser";

const config: GameConfig = {
  title: "Starfall",
  width: 800,
  height: 600,
  parent: "game"
  backgroundColor: "#18216D"
};

export class StarfallGame extends Phaser.Game {
  constructor(config: GameConfig) {
    super(config);
  }
}

window.onload = () => {
  var game = new StarfallGame(config);
};
```

Scene
```
import "phaser";

export class GameScene extends Phaser.Scene {

  constructor() {
    super({
      key: "GameScene"
    });
  }

  init(params): void {
    // TODO
  }

  preload(): void {
    // TODO
  }
  
  create(): void {
    // TODO
  }

  update(time): void {
    // TODO
  }
};

```

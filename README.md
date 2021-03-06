# Robotarm

Lees de instructies op de wiki pagina hoe de robotarm bibliotheek werkt. Vervolgens ga je proberen de onderstaande oefeningen te maken.

## Oefening 1
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 1");

  // Je eigen code plaats je hier.
   ------------------------------------
      robotArm.moveRight();
      robotArm.grab();
      robotArm.moveLeft();
      robotArm.drop();
   ------------------------------------
  robotArm.run();
</script>
```
Verplaats het rode blok één plek naar links.

![Oefening 1](readme/exercise1.png)

## Oefening 2
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 2");

  // Je eigen code plaats je hier.
------------------------------------
  robotArm.speed = (500);
  robotArm.loadLevel("exercise 2");
  robotArm.grab();

  for (var i = 1; i <= 9; i++) {
     robotArm.moveRight();
}

  robotArm.drop();

  for (var a = 1; a <= 5; a++) {
     robotArm.moveLeft();
}

robotArm.grab();

  for (var b = 1; b <= 5; b++) {
      robotArm.moveRight();
}

robotArm.drop();

robotArm.moveLeft();
robotArm.moveLeft();
robotArm.grab();
robotArm.moveRight();
robotArm.moveRight();

robotArm.drop();
            
robotArm.run();
  robotArm.run();
</script>
```
Stappel alle blokken op aan de rechterkant.

![Oefening 2](readme/exercise2.png)

## Oefening 3
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 3");

  // Je eigen code plaats je hier.
  
      for (var g = 1; g <= 4; g++) {
        robotArm.grab();
        robotArm.moveRight();
        robotArm.drop();
        robotArm.moveLeft();
      }

  robotArm.run();
</script>
```
Verplaats de hele stapel blokken één plek naar rechts.

![Oefening 3](readme/exercise3.png)

## Oefening 4
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 4");

  // Je eigen code plaats je hier.

            for (var i = 1; i <= 3; i++) {
              robotArm.grab();
              robotArm.moveRight();
              robotArm.moveRight();
              robotArm.drop();
              robotArm.moveLeft();
              robotArm.moveLeft();
            }

            robotArm.moveRight();
            robotArm.moveRight();
            robotArm.grab();
            robotArm.moveLeft();
            robotArm.drop();
            robotArm.moveRight();
            robotArm.grab();
            robotArm.moveLeft();
            robotArm.drop();
            robotArm.moveRight();
            robotArm.grab();
            robotArm.moveLeft();
            robotArm.drop();
            
  robotArm.run();
</script>
```
Verplaats de hele stapel blokken één plek naar rechts. Zorg ervoor dat de volgorde van de blokken gelijk blijft.

![Oefening 4](readme/exercise4.png)

## Oefening 6
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 6");

  // Je eigen code plaats je hier.

            for (var i = 1; i <= 7; i++) {
              robotArm.moveRight();
            }
            
            for (var a = 1; a <= 8; a++) {
              robotArm.grab();
              robotArm.moveRight();
              robotArm.drop();
              robotArm.moveLeft();
              robotArm.moveLeft();
            }

  robotArm.run();
</script>
```
Verplaats alle blokken één plek naar rechts. Zorg ervoor dat de volgorde van de blokken gelijk blijft. 

![Oefening 5](readme/exercise6.png)

## Oefening 7
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 7");

  // Je eigen code plaats je hier.
            
            for (var a = 1; a <= 5; a++) {
              for (var b = 1; b <= 6; b++) {
              robotArm.moveRight();
              robotArm.grab();
              robotArm.moveLeft();
              robotArm.drop();
            }
          robotArm.moveRight();
          robotArm.moveRight();
        }

  robotArm.run();
</script>
```
Verplaats iedere stapel één plek naar links.

Je mag maximaal 13 regels code gebruiken!

![Oefening 6](readme/exercise7.png)

## Oefening 8
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 8");

  // Je eigen code plaats je hier.


            robotArm.moveRight();
            robotArm.grab();

        for (var p = 1; p <= 7; p++) { 
            for (var i = 1; i <= 8; i++) {
                robotArm.moveRight();
            }
            robotArm.drop();

            for (var a = 1; a <= 8; a++) {
                robotArm.moveLeft();
            }
            robotArm.grab();
        }

  robotArm.run();
</script>
```
Verplaats de stapel naar de rechterkant.

Je mag maximaal 13 regels code gebruiken!

![Oefening 7](readme/exercise8.png)

## Oefening 9
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 9");

  // Je eigen code plaats je hier.

            for (var i = 1; i <= 4; i++) {
                for (var b = 1; b <= i; b++) {
                    robotArm.grab();
                
             for (var r = 1; r <= 5; r++) {
                    robotArm.moveRight();
                }

                robotArm.drop();

            for (var g = 1; g <= 5; g++) {
                    robotArm.moveLeft();
                }
            }
                robotArm.moveRight();

            }

  robotArm.run();
</script>
```
Verplaats alle stapels vijf stappen naar rechts.

Je mag maximaal 15 regels code gebruiken!

![Oefening 8](readme/exercise9.png)

## Oefening 10
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 10");

  // Je eigen code plaats je hier.

            for (var i = 9; i > 0; i = i-2) {
                robotArm.grab();

                for (var a = 0; a < i; a++) {
                robotArm.moveRight();
                    }
                    
                    robotArm.drop();

                for (var b = 0; b < i -1; b++) {
                robotArm.moveLeft();
                    }
                }

  robotArm.run();
</script>
```
Draai de volgorde van de blokken om.

Je mag maximaal 20 regels code gebruiken!

![Oefening 9](readme/exercise10.png)

## Oefening 11
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 11");

  // Je eigen code plaats je hier.

            for (var i = 1; i <= 9; i++) {
                robotArm.moveRight();
            }
            for (var a = 1; a <= 9; a++) {
            robotArm.grab();

            var color = robotArm.scan();

            if (color == "white"){
                robotArm.moveRight();
                robotArm.drop();
                robotArm.moveLeft();
            } else {
                robotArm.drop();
            }
            robotArm.moveLeft();
        }

  robotArm.run();
</script>
```
Verplaats alle witte blokken één plek naar rechts. 

Let op, de blokken zijn iedere keer anders als je het programma start!

![Oefening 10](readme/exercise11.png)

## Oefening 12
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 12");

  // Je eigen code plaats je hier.


            var color;
            robotArm.grab();
            color = robotArm.scan();
            var steps = 9;


        for (var i = 1; i <= 9; i++) {
            robotArm.grab();
            color = robotArm.scan();
            
            if (color == "red") {
               for (var a = 1; a <= steps; a++){
                 robotArm.moveRight();
               } 
                steps -=1;
                robotArm.drop();
                for (var b = 1; b <= steps; b++){
                    robotArm.moveLeft();
                }

            } else {
                steps -=1; 
                robotArm.drop();
                robotArm.moveRight();
            }
        }
        
  robotArm.run();
</script>
```
Verplaats alle rode blokken naar het einde.

Let op, de blokken zijn iedere keer anders als je het programma start!

![Oefening 11](readme/exercise12.png)

## Oefening 13
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.randomLevel( 1, 8);

  // Je eigen code plaats je hier.

  robotArm.run();
</script>
```
Verplaats alle blokken over de lege plaatsen, zodra er geen blokken meer zijn moet de arm stoppen.

[Bonus opdrachten](https://www.dropbox.com/s/7q4o3xboi5whgop/RobotArm%20Puzzels.docx?dl=0)

Succes!

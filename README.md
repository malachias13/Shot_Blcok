# Shot Block
Shot Block is a tile base puzzle game where the player can remotely activate turrets and reflect projectiles at enemies and destructible objects.

### **Objective**

As a Player, I want to remotely activate a turret to fire a single projectile, from which I can use my ability reflect refract (at the moment of almost hitting the player) to reflect the projectile in a certain direction.

## Shot block demo
 ![ReflectDemo](https://user-images.githubusercontent.com/69220988/165804050-95920426-0855-4044-a616-3a42bdcf789e.gif)
 
### **Using Reflect refract**

If the projectile approaching the player, before impact slow game time down to allow the player to select a direction for the projectile to reflect in.
Check each tile the projectile is heading in. If it is going to hit breakable wall, then break the wall when the ball reaches that tile.
Not using Reflect refract

The projectile will be destroyed on impacting the player.
Breakable and unbreakable walls

Breakable wall will only break on projectile impact.
Unbreakable will destroy projectile on impact.
What ever the projectile collide with will destroy the projectile.
 
 ## Enemy pathfinding
![Combact_System](https://user-images.githubusercontent.com/69220988/165804096-9bba2267-709d-4e97-9ab3-512fa42173f8.gif)



### Colision entre rectangles

```c++
	// Fonction detectCollision 
	 bool ObstacleRect::detectCollision(int leftCircleEdgeX,
	  int rightCicrleEdgeX,
	  int upperCircleEdgeY,
	  int bottomCircleEdgeY,
	  bool colidedAxe)
	// -> leftCircleEdgeX == Bord gauche 
	// -> rightCicrleEdgeX == Bord droit
	// -> upperCircleEdgeY == Bord supérieur
	// -> bottomCircleEdgeY == Bord inférieur
```

```c++
	// Attributs du rectangle (hitbox)
	this->leftAxeX ; // Bord gauche
	this->rightAxeX ; // Bord droit
	this->upperAxeY ; // Bord supérieur 
	this->bottomAxeY ; // Bord inférieur
```
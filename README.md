# TEMA_1_ACTIVIDAD_3_EJERCICIO_2
CIRCULO

package clases;
import java.awt.*;
public class Circulo implements Interfaz{
    public void Dibujo(Graphics g){
        g.drawOval(80, 50, 100, 100);
    }
    }
    
_CUADRADO

package clases;

import java.awt.*;


public class Cuadro implements Interfaz{
    @Override 
    public void Dibujo(Graphics g){ // creamos el metodo 
        g.drawRect(80, 60, 50, 50); // ubicacion y dimesion
        }
        }
        --------------------------------------------
INTERFAZ


package clases;

import java.awt.*;

interface Interfaz {
    void Dibujo (Graphics g); // dibujar figuras
}
----------------------------------------------
OVALO

package clases;

import java.awt.*;

public class Ovalo implements Interfaz{
    public void Dibujo(Graphics g){
        g.drawOval(80, 75, 120, 40); // ubicacion y dimension
}
}
---------------------------------------------
RECTANGULO



package clases;
import java.awt.*;
public class Rectangulo implements Interfaz{
    public void Dibujo(Graphics g){
        //posicion y mediadas de las figuras
        g.drawRect(90, 80, 100, 40
        }
        }
        ---------------------------------------------------
TRIANGULO


package clases;

import java.awt.*;

public class Triangulo implements Interfaz{
   
    public void Dibujo (Graphics g){
        
        int x []={142,110,190}; //puntos en X
        int y []={50,100,100}; // puntos en Y
        
        g.drawPolygon(x, y, 3); // dibujar el triango
    } 
    
}

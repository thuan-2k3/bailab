package bailab;

/**
 *
 * @author ADMIN
 */
public class Cirlce {
    private double radius;
    private double color;

    public Cirlce() {
    }
    

    public Cirlce(double radius, double color) {
        this.radius = radius;
        this.color = color;
    }

    public double getRadius() {
        return radius;
    }

    public void setRadius(double radius) {
        this.radius = radius;
    }

    public double getColor() {
        return color;
    }

    public void setColor(double color) {
        this.color = color;
    }
    public double getArea(){
        return radius*radius*3.14;
    }
    public String toString (){
        return "hinh mau"+color+" dien tich: "+getArea();
    }
    
}   

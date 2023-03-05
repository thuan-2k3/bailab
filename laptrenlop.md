package bailab;

/**
 *
 * @author ADMIN
 */
public class Cylinder extends Cirlce{
    private double height;

    public Cylinder(double height, double radius, double color) {
        super(radius, color);
        this.height = height;
    }
    
    public double getHeight() {
        return height;
    }

    public void setHeight(double height) {
        this.height = height;
    }
    public double getVolume(){
        return this.getArea()*height;
    }
}


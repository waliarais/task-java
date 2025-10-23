// Online Java Compiler
// Use this editor to write, compile and run your Java code online

class Main {
    
    Double area(Double side) {
        return side * side;
    }

    
    Double area(Double length, Double width) {
        return length * width;
        
    }
    
    Double area() {
        System.out.println("Area of shape is undefined");
        return 0.0;
    }

    
    public static void main(String[] args) {
        Main obj = new Main();

        System.out.println("Area of square: " + obj.area(5.0));
        System.out.println("Area of rectangle: " + obj.area(5.0, 3.0));
        obj.area(); 
    }
}

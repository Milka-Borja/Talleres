import java.util.Scanner;
public class Empleado {
    String nombre;
    String cargo;
    double salario;
    String fecha;
    public Empleado(String nombre, String cargo, double salario, String fecha) {
        this.nombre=nombre;
        this.cargo=cargo;
        this.salario=salario;
        this.fecha=fecha;


    }
    void mostrar(){
        System.out.println("Nombre: "+nombre+"Cargo: "+cargo+"Salario: "+salario+"Fecha: "+fecha);
    }
    public static void main(String[] args){
        Scanner ingreso= new Scanner(System.in);
        System.out.println("--------------Empleado 1-------------------");
        System.out.println("Ingrese el nombre del empleado: ");
        String name1=ingreso.nextLine();
        System.out.println("Ingrese el cargo del empleado: ");
        String cargo1=ingreso.nextLine();
        System.out.println("Ingrese el salario del empleado: ");
        double salario1=ingreso.nextDouble();
        ingreso.nextLine();
        System.out.println("Ingrese el fecha del empleado: ");
        String fecha1=ingreso.nextLine();
        System.out.println("--------------Empleado 2-------------------");
        System.out.println("Ingrese el nombre del empleado: ");
        String name2=ingreso.nextLine();
        System.out.println("Ingrese el cargo del empleado: ");
        String cargo2=ingreso.nextLine();
        System.out.println("Ingrese el salario del empleado: ");
        double salario2=ingreso.nextDouble();
        ingreso.nextLine();
        System.out.println("Ingrese el fecha del empleado: ");
        String fecha2=ingreso.nextLine();
        System.out.println("Ingrese el nombre del empleado: ");
        System.out.println("--------------Empleado 3-------------------");
        String name3=ingreso.nextLine();
        System.out.println("Ingrese el cargo del empleado: ");
        String cargo3=ingreso.nextLine();
        System.out.println("Ingrese el salario del empleado: ");
        double salario3=ingreso.nextDouble();
        ingreso.nextLine();
        System.out.println("Ingrese el fecha del empleado: ");
        String fecha3=ingreso.nextLine();




    }
}

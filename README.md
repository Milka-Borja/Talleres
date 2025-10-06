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








import java.util.Scanner;
public class Jugador {
    String nombre;
    String posicion;
    int edad;
    int camiseta;
    public Jugador(String nombre, String posicion, int edad, int camiseta){
        this.nombre = nombre;
        this.posicion = posicion;
        this.edad = edad;
        this.camiseta = camiseta;
    }
    void mostrar(){
        for(int i=1; i<=3; i++){
            System.out.println("Jugador n°"+i+"\n Nombre: "+nombre+" \n Posicion: "+posicion+"\n Edad: " +edad+" \n Camiseta: "+camiseta);
        }
    }
    public static void main(String[] args){
        Scanner ingreso= new Scanner(System.in);
        System.out.println("Ingrese el nombre del jugador:");
        String name1=ingreso.nextLine();
        System.out.println("Ingrese el posicion del jugador:");
        String pos1=ingreso.nextLine();
        System.out.println("Ingrese la edad del jugador:");
        int edad1=ingreso.nextInt();
        System.out.println("Ingrese el numero de camiseta deljugador: ");
        int cam1=ingreso.nextInt();
        ingreso.nextLine();
        System.out.println("----------------Jugador 2----------------");
        System.out.println("Ingrese el nombre del jugador 2:");
        String name2=ingreso.nextLine();
        System.out.println("Ingrese el posicion del jugador 2:");
        String pos2=ingreso.nextLine();
        System.out.println("Ingrese la edad del jugador 2:");
        int edad2=ingreso.nextInt();
        System.out.println("Ingrese el numero de camiseta deljugador 2: ");
        int cam2=ingreso.nextInt();
        ingreso.nextLine();
        Jugador jugador1=new Jugador(name1,pos1,edad1,cam1);
        Jugador jugador2=new Jugador(name2,pos2,edad2,cam2);
        Jugador jugador3=new Jugador("Jose","delantero",23,5);
        jugador1.mostrar();//Fin del Programa
    }
}












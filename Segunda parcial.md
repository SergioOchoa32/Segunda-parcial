<h1>Universidad de Colima</h1>
<h2>Facultad de ingenieria mecanica y electrica</h2>
<h2>Ingenieria en computacion inteligente</h2>
<h2>Alumno: Sergio Valentin Ochoa Hernandez</h2>
<h2>Maestro: Dr. Walter Alexander Mata</h2>

<h3>Tipado</h3>

    void main(){
      int miEntero=10;
      double miDouble = 3.14.16;
      print(miEntero);
      print(miDouble);
      num miNumber1=10;
      num miNumber2=3.1416;
      print(miNumber1);
      print(miNumber2);
      String miString = "Hola";
      print(miString);

<h3>declaracion var</h3>

    void main(List<String> args){
      int nHexa=0xF;
      int nHexa=0xF;
      
      print(nHexa1 * nHexa2);
      }
<h3>Switch case</h3>
    
    void main(List<String> args){
      var dia;
      dia="Martes";
      
      switch (dia) {
        case "Lunes":
          print("Hoy es Lunes");
          break;
        case "Martes":
          print("Hoy es Martes");
          break;
        default:
          print("Dia no conocido");
          }}

<h3>ciclos</h3>

      void main(List<String> args){
        var numeros = ["1", "2", 3.1416, true, 5];
        for (var e in numeros) {
          print("$e");
        }
        
        numeros.forEach((e) {}); {
          print("$e");
        });
      
<h3>clases</h3>

      class User {
        String? nombre;
        int? edad;
      }
      
      void main(List<String> args) {
        User usuario1 = User();
        var usuario 2 =User();
        
        usuario1.nombre = "Alex";
        usuario1.edad = 50;
        usuario2.nombre = "Jimena";
        usuario2.edad = 11;
        
        print(usuario1.nombre);
        print(usuario1.edad);
        print(usuario2.nombre);
        print(usuario2.edad);

<h3>clases y atributos</h3>

      class User {
        String? nombre;
        int? edad;
      
        void reporte () {
          print("Nombre:$nombre");
          print("Edad:$edad anios");
        }  
      }
      
      void main(List<String> args) {
        user usuario1 = User();
        usuario1.nombre = "Alex";
        usuario1.edad = 50;
        
        usuario1.reporte();
        
<h3>Incrementos y decrementos</h3>

    void main(List<String> args) {

     var contador=0;

     contador=contador+1;
     print(contador);
     contador+=1;
     print(contador);
     contador++;
     print(contador);
     ++contador;
     print(contador);

     var c=10;
     print(++c);//11
     c=10;
     print(c++); //10
     print(c);
    }
    // DECREMENTOS
    void main(List<String> args) {

      var contador = 0;

      contador = contador - 1;
      print(contador);
      contador -= 1;
      print(contador);
      contador--;
      print(contador);
      --contador;
      print(contador);

      var c = 10;
      print(--c); //11
      c = 10;
      print(c--); //10
      print(c);
    }
        
<h3>Constructores</h3>

      class User {
        User() {
          print("Constructor User");
        }
      }
      
      void main(List<String> args) {
        final usuario1 = User();
        print(usuario1);
      }

<h3>constructores getter y setter</h3>

      class User {
        String? nombre;
        int? edad;
        
        void set nombre (String nombre) {
          _nombre = nombre;
        }
        
        String get nombre {
          return _nombre!;
          }
          
        void reporte() {
          print("Nombre: $_nombre");
          print("Edad: $_edad anios");
        }
      }
      
      void main(List<String> args) {
        final usuario1 = User();
        usuario1.nombre = "Alex";
        print(usuario1.nombre);
        usuario1.reporte();
      }
      
<h3>constructores getter y setter 2</h3>

     void main() {
      User usuario = User.nombre("Sergio");
      User usuario2 = User.edad(18);
      usuario.reporteUser();
      usuario2.reporteUser();
    }
    class User {
      String? nombre;
      int? edad;
      void reporteUser() {
        print(nombre);
        print(edad);
      }
      User.nombre(this.nombre);
      User.edad(this.edad);
      void set setNombre(String nombre) => nombre = nombre;
      void set setEdad(int edad) => edad = edad; 
      String get getNombre => nombre!;
      int get getEdad => edad!;
    }


<h3>constructores con propiedades</h3>

      class User {
        String? nombre;
        int? edad;
        
        User ({this.nombre, this.edad});
        
        String? get getNombre => nombre;
        int? get getEdad => edad;
      }
      
      void main(List<String> args) {
        final usuario1 = User(nombre: "Alex", edad:50);
        print(usuario1.nombre);
        print(usuario1.edad);
      }

<h3>Herencia</h3>

      class Estudiante {
        String nombre = "";
        int edad = 0;
        
        void mostrarDatos() {
            print("Nombre: $nombre");
            print("Edad: $edad");
          }
        }
        
        class Estudiante extends User{}
        
        class Profesor extends User{}
        
        class Directivo extends User{}
        
        void main(List<String> args) {
            final estudiante1 = Estudiante();
            estudiante1.nombre = "Hugo";
            estudiante1.edad = 15;
            estudiante.mostrarDatos();
            final profesor1 = Profesor();
            profesor1.nombre = "Paco";
            profesor1.edad = 16;
            profesor1.mostrarDatos();
            final directivo1 = Directivo();
            directivo1.nombre = "Luis";
            directivo1.edad = 17;
            directivo1.mostrarDatos();

<h3>Ciclos en Dart</h3>

    void main() {
      final calificacion = [10, 6, 9, 8, 10, 8];
      print(calificacion);
      calificacion.add(2); 
      print(calificacion);
      for (var i = 0; i < calificacion.length; i++) {
        print(calificacion[i]);
      }
    }
    void main(List<String> args) {
      for (var i = 1; i < 5; i++) {
        print("$i");
      }
      var numeros = [1, 2, 3, 4, 5];
      for (var e in numeros) {
        print("$e");
      }
    }

    void main() {
      var numeros = ["1", "2", 3.1415, true, 5];
      for (var e in numeros) {
        print("$e");
      }
      numeros.forEach((e) {
        print("$e");
      });
    }

<h3>Runtime</h3>

    void main() {
      final calificacion = [10, 6, 9, 8, 10, 8];
      print(calificacion);
      calificacion.add(2); 
      print(calificacion);
      for (var i = 0; i < calificacion.length; i++) {
        print(calificacion[i]);
      }
    }
    void main(List<String> args) {
      for (var i = 1; i < 5; i++) {
        print("$i");
      }
      var numeros = [1, 2, 3, 4, 5];
      for (var e in numeros) {
        print("$e");
      }
    }

    void main() {
      var numeros = ["1", "2", 3.1415, true, 5];
      for (var e in numeros) {
        print("$e");
      }
      numeros.forEach((e) {
        print("$e");
      });
    }

<h3>Preexamen</h3>

    void main() {
      Vehiculo miNave = Vehiculo(4, "blanco", "Tesla", "2023");
      print(miNave.getllantas);
      print(miNave.getColor);
      print(miNave.getMarca);
      print(miNave.getModelo);

      miNave.estacionar();
      miNave.encenderr();
      miNave.frenar();
    }

    class Vehiculo {
      int? _nollantas;
      String? _marca;
      String? _modelo;
      String? _color;
      String? _automovil;

      void estacionar() {
        print("Estacionar");
      }

      void frenar() {
        print("Frenando");
      }

      void encenderr() {
        print("Encendido");
      }

      Vehiculo(int llantas, String color, String marca, String modelo) {
        this._nollantas = llantas;
        this._color = color;
        this._marca = marca;
        this._modelo = modelo;
      }

      void set setLlantas(int llantas) => _nollantas = llantas;
      int get getllantas => _nollantas!;

      void set setMarca(String marca) => _marca = marca;
      String get getMarca => _marca!;

      void set setModelo(String modelo) => _modelo = modelo;
      String get getModelo => _modelo!;

      void set setColor(String color) => _color = color;
      String get getColor => _color!;
    }


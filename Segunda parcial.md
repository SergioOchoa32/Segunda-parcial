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

<h3></h3>

<h3></h3>

<h3></h3>

<h3></h3>

<h3></h3>

<h3></h3>

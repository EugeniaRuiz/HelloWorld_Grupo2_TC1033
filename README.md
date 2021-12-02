## HelloWorld_Grupo2_TC1033
# Eugenia Ruiz Velasco Olvera
## Laboratorio - branch - commits  - pull request - merge - markdown


**bold text**

*italicized text*

1. GitHub
2. Método de calcular als frecuencias
3. Descargar los nuevos archivos de Series y Episodios

- GitHub
- Método de calcular als frecuencias
- Descargar los nuevos archivos de Series y Episodios

	```` c++
  //
  //  main.cpp
  //  Proyecto-Avance1
  //
  //  Created by Eugenia Ruiz Velasco Olvera A01177887 on 11/11/21.
  //

  // Apendizajes entrega 2 / Actividad: Composición:
  // Para esta entrega del segundo avance, se esperaba que hicieramos una composición de Episodio con Serie. A primera instancia pensé que no iba a batallar tanto pero si tuve algunas complicaciones que con asesoría pude ir comprendiendo. Analizar el funcionamiento de las diferentes partes del código fue mucho más sencillo el comprendimiento junto con varios ejemplos de prueba para entender mejor como funcionaba. Aprendí el excelente uso de composicón al momento de hacer códigos que involucren varias clases y como se pueden entrelazar entre sí y poder tener miembros de una clase en otra.

  #include <iostream>
  #include "Serie.hpp"
  #include "Episodio.hpp"
  #include "Series.hpp"
  using namespace std;

  void leerSerie(std::string &_id, std::string &_titulo, int &_duracion, std::string &_genero, double &_calificacionPromedio, int &_cantEpisodios){
    
    cout << "Ingrese el ID: ";
    cin >> _id;
    cout << "Ingrese el título: ";
    cin >> _titulo;
    cout << "Ingrese la duración (en minutos): ";
    cin >> _duracion;
    cout << "Ingrese el género: ";
    cin >> _genero;
    cout << "Ingrese la calificación promedio: ";
    cin >> _calificacionPromedio;
    cout << "Ingrese la cantidad de episodios: ";
    cin >> _cantEpisodios;
    
    }
  
  ````
  
  
  
----
  
[mardownguide.org](https://www.markdownguide.org/cheat-sheet/)

![Relajada en una playa del Caribe](playita.jpeg)
  
  
  
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

- [x] Pozole
- [ ] Pizza
- [ ] Pastel de chocolate
  
  
  

@startuml
scale 3

abstract class Poligono{
    *area(): int
    *perimetro(): int
}
class Triangulo{
    -alpha, bheta, gama: int 
    -a,b,c: float
    -base, alt: float
}
class Cuadrilatero{
    -alpha, bheta, gama: int 
    -a,b: int
    -base, alt: int
}
class Object{
}
interface InstrumentoMusical{
    *tocar():void 
    *afinar(): void
    *tipoInstrumento(): String
}
class InstrumentoViento{

}
class Flauta{
    *@override
    *tipoInstrumento(): String
}
interface Meses{
    -UNO, DOS,..., DOCE: int
    NOMBRE_MESES[]:String
}

Poligono <|---Triangulo
Poligono <|---Cuadrilatero

Object <|---InstrumentoViento
InstrumentoMusical <|---InstrumentoViento : Interfaz
InstrumentoViento <|---Flauta
@enduml
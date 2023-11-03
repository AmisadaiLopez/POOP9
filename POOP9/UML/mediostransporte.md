@startuml
scale 3 

abstract class MediosTransporte{
    -nombre: String
    -combustible: String
    *iniciarViaje(): void
    *finalizarViaje(): void
    *encender(): void
    *apagar(): void
}

class TransporteTerrestere{
    -velocidad: int
    -capacidad: String
    *acelerar(): void
    *frenar(): void
}
class Subterraneo{
    -costo: int
    *iniciarViaje(): void
}
class Metro{
    -estacion: String
    -ciudad: String
    *abordar(): void
    *descender(): void
}
class Suburbano{
    -horario: String
    -ciudad: String
    *iniciarViaje():void 
    *finalizarViaje(): void
    *consultarHorario(): void
}
class Supraterraneo{
    -vehiculo: String
    *calcularTarifa(): void
    *verificarDisponibilidad(): void 
}
class Taxi{
    -tarifaBase: String
    -disponible: String
    *iniciarViaje(): void
    *terminarViaje(): void 
}
class Combi{
    -ruta: String
    *iniciarViaje(): void
    *finalizarViaje(): void
}


class TransporteAcuatico{
    -velocidad: int 
    -capacidad: String 
    *aumentarVelocidad(): void 
    *disminuirVelocidad(): void
}
class Barco{
    -puertoOrigen: String
    -puertoDestino: String
    *abordarPasajeros(): void
    *desembarcarPasajeros(): void
}
class Trajinera{
    -nombre: String
    *iniciarPaseo():
}


class TransporteAereo{
    -velocidad: int
    -capacidad: String
    *despegar(): void
    *aterrizar(): void
}
class Avion{
    -aeropuerto: String
    -piloto: String
    *despegar(destino): void
    *aterrizar(aeropuerto): void
}
class Helicoptero{
    -numeroDeRegistro: int 
    -ubicacion: String
    *despegar(destino): void
    *aterrizar(coordenadas): void
}

MediosTransporte <|---TransporteTerrestere
TransporteTerrestere <|---Subterraneo
Subterraneo <|---Metro
Subterraneo <|---Suburbano
TransporteTerrestere <|---Supraterraneo
Supraterraneo <|---Taxi
Supraterraneo <|--- Combi

MediosTransporte <|--TransporteAcuatico
TransporteAcuatico <|---Barco 
TransporteAcuatico <|---Trajinera 

MediosTransporte <|---TransporteAereo
TransporteAereo <|---Avion
TransporteAereo <|--- Helicoptero
@enduml
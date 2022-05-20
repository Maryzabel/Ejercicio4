# Ejercicio4
En R con el uso de dataframe realiza una baraja del juego de cartas (no usar for)

conjunto_cartas<-c("A",2:10,"J","Q","K")
cartas<-c(rep(conjunto_cartas,4))
conjunto_tipos<-c("Corazon", "Diamante", "Trebol", "Espada")
tipos<-c(rep(conjunto_tipos,rep(13,4)))
conjunto_figuras<-c("♥", "♦", "♣", "♠")
figura<-c(rep(conjunto_figuras,rep(13,4)))
baraja=data.frame(cartas,tipos,figura)
baraja

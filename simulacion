# Simulación de rendimiento (Ejemplo)
set.seed(123)
design$Rendimiento <- with(design, 50 + 20*Fertilizante_A + 15*Fertilizante_B + 
                                   10*Fertilizante_A*Fertilizante_B - 
                                   5*Fertilizante_C*Fertilizante_B + 
                                   rnorm(nrow(design), sd = 5)) # Variabilidad aleatoria

# Ver los datos simulados
head(design)

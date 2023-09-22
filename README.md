# actividadesprimerparcial
estos son mis códigos de primer parcial

CODIGO DE MAQUINA DE FUNCIONES:
from re import X

def f(x): #haciendo mi cajita feliz
  f_x=abs(3*x)
  return f_x

y= f(10) #pucharle play con 10 de input 

print (y)

def g(x): #haciendo mi cajita feliz 
  f_x=-2*x+34
  return f_x 
  
y=f(2)
print(y) #imprimiendo nuestro outfit en la consola

def f(x):
  f_x=-x/3-10
  return f_x 

y=f(6)
print(y)

def f(y):
  f_x=(X-2)**2
  return f_x

y=f(7)

print(y)


1 CODIGO DE CODING RUSH:
"""¿Por qué me termino mi ex?"""
def función_feliz 
  print( "¿Quieres saber por qué te termino tu ex?")
  si=input()
  print("te lo dire por el nombre de quten era el ex")
  print("elige el primer que mas te guste. Juan, Carlos o Estreban")
  Juan=input()
  print( "el ex que mas me dolioo fue Juan")
  perefecto-input().
  Carlos=input()
  print("El ex que casi no me gustaba era Carlos")
  wow=input()
  Esteban=input()
  print( "Esteban era muy bueno conmigo")
  estabien=input()
  print( "fue un honor"
  
  palabras=lent()

funcion_feliz()


1 CODIGO QUE IMPRIMA "HOLA MUNDO":
print=("hola mundo")


2 EJERCICIOS DE REPASO EXAMEN:
"""convertir una temperatura en grados Celsius"""
def funcion_triste():
  print("¿Quieres la temperatura en grados Celsius?")
  si=input()
print("aqui estan las tres formas de temperatura")
print("celsius 17, farenheit 62, kelcin 190")

STEP 1
def name():
  print("introduzca la propina de comida")
  propina = input()
  print("introduzca cantidad de propina en porcentaje")
  descuento = input()
  precio = 100+int(descuento)
  multiplicacion = (int(propina)/100)*precio
  print("Propina final",multiplicacion)
#STEP 2
name()



1 CODIGO DEL EXAMEN PARCIAL:
#Perro Robot Examen Codigo
class PerroRobotInteligente:
    def __init__(self):
        self.registro_imc = []

    def calcular_imc(self, peso, altura):
        imc = peso / (altura ** 2)
        self.registro_imc.append(imc)

    def mostrar_imc(self):
        if len(self.registro_imc) >= 2:
            imc_semana1 = self.registro_imc[-2]
            imc_semana2 = self.registro_imc[-1]
            print(f"IMC en la semana 1: {imc_semana1:.2f}")
            print(f"IMC en la semana 2: {imc_semana2:.2f}")
        else:
            print("No hay suficientes registros para mostrar dos IMCs.")

# Altura constante para el paciente
altura_paciente = 1.68

# Crear el perro robot
perro_robot = PerroRobotInteligente()

# Calcular IMC en la semana 1 y semana 2
peso_semana1 = 75
peso_semana2 = 73

perro_robot.calcular_imc(peso_semana1, altura_paciente)
perro_robot.calcular_imc(peso_semana2, altura_paciente)

# Mostrar los resultados de IMC
perro_robot.mostrar_imc()    




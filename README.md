# Repo-na-programowanie
zadanko
# #zadanie4
lista=[1,2,3,4,5,6,7,8,9]
lista2=[10,20,30,40]
def dlugosc(lista):
    if len(lista)>0:
        return 1+dlugosc(lista[1:])
    else:
        return 0
print(dlugosc(lista))

# pyevents

## EN-US
A small library developed with Python 3.6 that implements Observer pattern using RLock to achieve thread synchronization;

This library consists of just two abstract classes:
* Observer
  > The class that marks that the subclass should receive notifications from Observable objects of interest
* Observable
  > The class responsible for maintain the controll of Observer classes interested in receiving notifications. It's also possible to pass arguments to those classes.

## PT-BR
Uma pequena biblioteca desenvolvida com Python 3.6 que implementa o padrão Observer usando RLock para sincronização de threads;

Esta biblioteca consiste em apenas duas classes abstratas:
* Observer
    > Classe que identifica que a Subclasse deverá receber notificações vindas dos objetos Observable de interesse.
* Observable
    > Classe que é responsável por manter o controle das classes Observer interessadas em receber notificações. Também é possível passar argumentos para essas classes interessadas.

# Übung 2: Array mit Werten füllen

In dieser Übung verwenden sie Divide And Conquer, um ein Array mit Werten zu befüllen. Machen sie die Übung **alleine**.

## 1. Schritte

1. Verwenden sie den Code unten als Basis.

2. Implementieren sie den folgenden Algorithmus

   1. Teile das Array jeweils in der Mitte.
   2. Wenn das Array eine Länge von 1 hat, füllen sie den Wert 'X' an der entsprechenden Position ein.
   3. Achtung: Sie müssen das Array nicht wirklich teilen. Sie übergeben jeweils den Start- und End-Index (wie im Code unten vorgegeben).

   

## 2. Code Basis

~~~java
public class DivideAndConquer {
    private char[] list;

    public void Run(int n){
        list = new char[n];
        java.util.Arrays.fill(list, '-');
        Fill(0, list.length-1);
    }

    private void Fill(int from, int to){
        
    }
}
~~~








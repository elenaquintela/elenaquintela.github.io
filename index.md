# Elena

## Mis proyectos

- Código java
```
 public class ejercicio2 {
    public static void main(String[] args) {
        Scanner escaner = new Scanner(System.in);
        String[] nomes = new String[4];
        for (int i = 0; i < nomes.length; i++) {
            System.out.print("Introduce o nome da persoa " + (i + 1) + ": ");
            nomes[i] = escaner.nextLine();
        }
        String saudo = "Ola ";
        for (int i = 0; i < nomes.length; i++) {
            saudo += nomes[i];
            if (i < nomes.length - 1) {
                saudo += ", ";
            }
        }
        saudo += "!";
        System.out.println(saudo);

        escaner.close();
    }
 }
```

```BASH
ls
```

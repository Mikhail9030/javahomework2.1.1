## Задание №1

* Стоимость билета Москва - Якутск 15600 (средняя стоимость)
* Бонус за каждые 20 руб - 1 миля = 0.05%
* Java код:

### public class MainV1 {
    * public static void main(String[] args) {
        boolean registered = true;
        float amount = 15600.0F;
        float percent = 0.05F;

        float bonus = amount * percent;
        System.out.println(bonus);
    }
}

### "C:\Program Files\AdoptOpenJDK\jdk-11.0.9.101-hotspot\bin\java.exe" -javaagent:C:\Users\Acer\AppData\Local\JetBrains\Toolbox\apps\IDEA-C\ch-0\203.5981.155\lib\idea_rt.jar=2250:C:\Users\Acer\AppData\Local\JetBrains\Toolbox\apps\IDEA-C\ch-0\203.5981.155\bin -Dfile.encoding=UTF-8 -classpath C:\Users\Acer\IdeaProjects\untitled\out\production\untitled MainV1
780.0

Process finished with exit code 0

* Итого программа рассчитала - 780 миль.
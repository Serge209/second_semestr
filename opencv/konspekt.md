Функция состоит из трех частей: Тип данных, Имя функции, Аргументы(у каждого аргумента есть тип данных).

1. List<Mark> GetMarks (DateTime now, List<string> students) {
  List<Mark> Ret = new List<Mark>();
  return Ret;
  }
  double MinAVG(string [] marks) {
  double k = 8.9;
  return k;
  }
  int[] GetCountTruancy(List<Mark> marks) {
  int[] l = new int();
  return l;
  }
  int[] GetCountDisease (List<Mark> marks) {
  int[] m = new int();
  return m;
  }
  string GetStudNumber (int year, int group, string fio) {
   string o = "Ivan";
   return o;
  }
  
  1. List<Mark> - Список оценок. GetMarks - получить оценки. DateTime now, List<string> students - Сегодняшняя дата и список со студентами
  2. double - дроби. MinAVG - Минимальное среднее значение. string [] marks - Массив оценок.
  3. int[] - Массив. GetCountTruancy - количество прогулов . List<Mark> marks - Список оценок.
  4. int[]  - Массив. GetCountDisease - количество пропусков по болезни. List<Mark> marks - Список оценок.
  5. string - строка. GetStudNumber - номер студ билета. int year, int group, string fio - Год, Группа, ФИО.
  
  Функция может быть: Прописана до main или вызвана в main.
  Копируем тип данных функции, если он сложный выбираем имя переменной(можно везде ret) = Новый элемент(new) с типом данным функции() возвращаем результат командой return Ret, то что в фигурных скобках - тело функции.
  Простые типы данных это (string, int, double, char) 
  Для вызова в main копируем имя функции и ее аргументы, убрав тип данных. Тип данных функции появляется у переменной в котрую мы хотим записать результат работы функции, тип данных аргументов передается переменным объявленных до функции.
 1. DateTime n;
  List<string> U;
  List<Mark> J = GetMarks (now, students);
  
 2. string [] p;
  double k = MinAVG (marks);
  
 3.List<Mark> Y;  
 int[] g = GetCountTruancy (marks);
  
 4.List<Mark> Z;  
 int[] g = GetCountDisease (marks);
  
 5. int i;
    int f;
    string o;
    string m = GetStudNumber ( year,  group,  fio);
  
  
  
 

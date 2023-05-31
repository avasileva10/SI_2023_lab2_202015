# SI_2023_lab2_202015
Анастасија Василева 202015 ИМБ 
CFG 
![CFG](https://github.com/avasileva10/SI_2023_lab2_202015/assets/72934658/2bd754cd-23c1-4f51-9217-405f793de2d3)
Цикломатска комплексност ја пресметав со предикатна логика односно во задачава е 2.


Тест случаеви кои поминуваат низ сите патеки се следниве:
" " , " " , " "
null, "anastasija" , anastasija@googlecom
"anastasija","#haker123","anastasija@google.com
Unit тестовите ми се подетални и тоа се следниве:
1) User user=null;

2)User user = new User(null, "password", "email@example.com");

3)User user = new User("username", "password", "email@example.com");
List<User> allUsers = new ArrayList<>();
allUsers.add(new User("another", "anotherPassword", "email@example.com"));

4)User user = new User("username", "password", "email@example.com");
  List<User> allUsers = new ArrayList<>();

5)User user = new User("username", "pass", "email@example.com");
        List<User> allUsers = new ArrayList<>();

6) User user = new User("username", "password!", "email@example.com");
        List<User> allUsers = new ArrayList<>();

7)User user = new User("username", "!#password", "email@example.com");
        List<User> allUsers = new ArrayList<>();

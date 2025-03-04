
<h1><img src="https://media.giphy.com/media/ZeLcIBH7lKfLOkaBRH/giphy.gif" width="50"> I'm seokho  </h1>


<img align='right'  src="http://mazassumnida.wtf/api/v2/generate_badge?boj=gjrehf" width="300">

Welcome to my page!<br>
I wanna be a Front-End Developer

### seokHo_kim.dart <img src="https://media.giphy.com/media/AQgnKLF0QfLzyDO538/giphy.gif" width="150" padding="0">

 
````dart
class Developer {
  final String name;
  final List<String> code;
  final List<String> tools;
  final List<String> os;
  final String email;
  final String status;

  const Developer({
    required this.name,
    required this.code,
    required this.tools,
    required this.os,
    required this.email,
    required this.status,
  });
}

void main() {
  Developer seokHo = Developer(
    name: "seokho",
    code: ["Dart", "Javascript", "Typescript", "HTML", "CSS", "C++"],
    tools: ["Flutter", "React", "ReactNative", "Redux", "Styled-Components"],
    os: ["Windows", "MacOs"],
    email: "gjrehf@gmail.com",
    status: "I have a crush on Flutter",
  );
}


# Calculator in Flutter
Basic calculator developed using dart and flutter.

To run this app 'math packages' must be installed into your IDE whether it is android studio or VS Code.
The math expressions version must be mentioned in the pubspec.yaml file in order to run the code.

Try catch method is used as logic for math calculations.

try{
          Parser p = Parser();
          Expression exp = p.parse(expression);
          ContextModel cm = ContextModel();
          result = '${exp.evaluate(EvaluationType.REAL, cm)}';
        }catch(e){
          result = 'Error';
        }


The above code is after you import math packages into your main.dart file.


import 'package:flutter/material.dart';
import 'pages/home.dart';

void main() => runApp (MaterialApp(
  home:  NinjaCard(),
));

class NinjaCard extends StatefulWidget{
  @override
  State<NinjaCard> createState() => _NinjaCardState();
}

class _NinjaCardState extends State<NinjaCard> {




//crea el archivo dart nuevo en libreria y geestion
  int ninjaLevel = 0;


  @override
  Widget build(BuildContext context) {
    return Scaffold(appBar: AppBar(
      title: Text('Nombre de la aplicación'),
      centerTitle: true,
      backgroundColor: Colors.red,
    ),
      body: Column(

        mainAxisAlignment: MainAxisAlignment.start,
        crossAxisAlignment: CrossAxisAlignment.stretch,
        children: [

          Column(

          ),

          Container(
            padding: EdgeInsets.all(02.0),
            color: Colors.yellow,
            child: Row(
              children: [
                Expanded(
                  flex: 2,
                  child: Container(
                    padding: EdgeInsets.all(30.0),
                    color: Colors.cyan,
                    child: Text('Inicio'),
                  ),
                ),
                Expanded(
                  flex: 4,
                  child: Container(
                    padding: EdgeInsets.all(30.0),
                    color: Colors.pinkAccent,
                    child: Text('Catálogo'),
                  ),
                ),
                Expanded(
                  flex: 1,
                  child: Container(
                    padding: EdgeInsets.all(30.0),
                    color: Colors.amber,
                    child: Text('login'),
                  ),
                ),
              ],
            ),


          ),
          Container(
            padding: EdgeInsets.all(02.0),
            color: Colors.yellow,
            child: Row(
              children: [
                Container(
                  padding: EdgeInsets.all(30.0),
                  color: Colors.cyan,
                  child: Text('$ninjaLevel'),
                ),
                Container(
                  padding: EdgeInsets.all(30.0),
                  color: Colors.pinkAccent,
                  child: Text('2'),
                ),
                SizedBox(width: 10.0),
                Container(
                  padding: EdgeInsets.all(30.0),
                  color: Colors.amber,
                  child: Text('3'),
                ),
                Text(
                    'Name',
                    style: TextStyle(
                      color: Colors.grey,
                      letterSpacing: 2.0,
                    )
                ),
                Text(
                    'Penelope',
                    style: TextStyle(
                        color: Colors.grey,
                        letterSpacing: 2.0,
                        fontSize: 28.0,
                        fontWeight: FontWeight.bold
                    )
                ),
                CircleAvatar(
                  backgroundImage: AssetImage('assets/dd.jpg'),
                  radius: 20.0,
                ),
                Center(
                  child: Image.asset('assets/dd.jpg'),
                ),
              ],
            ),
          ),
          Container(
            padding: EdgeInsets.all(02.0),
            color: Colors.pink,
            child: Row(
              children: [
                Expanded(
                  flex: 1,
                  child: Image(
                    image: NetworkImage(
                        'https://media.gettyimages.com/photos/beautiful-girl-red-background-picture-id1157172541?k=20&m=1157172541&s=612x612&w=0&h=Bf2puUDRB-2DZvosB5qZssE6IeSJ7if5YYobAYElxCQ='),),
                ),
                Expanded(
                  flex: 1,
                  child: Container(
                    padding: EdgeInsets.all(30.0),
                    color: Colors.cyan,
                    child: Text('1'),
                  ),
                ),
                Expanded(
                  flex: 1,
                  child: Image(
                    image: NetworkImage(
                        'https://previews.123rf.com/images/stockbroker/stockbroker1702/stockbroker170201314/71266791-retrato-de-dos-ni%C3%B1as-que-juegan-en-el-oscilaci%C3%B3n-del-neum%C3%A1tico-en-jard%C3%ADn.jpg'),),
                ),
              ],
            ),
          ),

          Row(
//properties
            mainAxisAlignment: MainAxisAlignment.spaceEvenly,
//crossAxisAlignment: CrossAxisAlignment.start,
            children: [
              Text('Hello'),
              Icon(
                Icons.airport_shuttle,
                color: Colors.black,
                size: 20.0,),
              RaisedButton(
                onPressed: () {
                  print('you are the best');
                },
                child: Text('shadow'),
                color: Colors.cyan,
              ),

              RaisedButton.icon(
                onPressed: () {
                  print('you are the best');
                },
                icon: Icon(
                    Icons.mail
                ),
                label: Text('Mail me'),
                color: Colors.redAccent,
              ),
              FlatButton(
                onPressed: () {
                  print('eres el mejor');
                },
                child: Text('Echale'),
                color: Colors.cyan,
              ),
              IconButton(
                  onPressed: () {
                    print('Haaa');
                  },
                  icon: Icon(Icons.alternate_email),
                  color: Colors.amber
              ),
              Expanded(
                flex: 1,
                child: Image(
                  image: NetworkImage(
                      'https://img1.freepng.es/20180412/rxq/kisspng-ipma-email-telephone-message-email-icon-5acf36453ee1e1.3103384815235292852576.jpg'),),
              ),
              Container(
                padding: EdgeInsets.all(20.0),
//padding: EdgeInsets.fromLTRB(10.0,15.0,10.0,15.0),
//padding: EdgeInsets.symmetric(20.0),
                margin: EdgeInsets.all(20.0),
                color: Colors.amberAccent,

                child: Text('Hello again',
                  style: TextStyle(
                    fontSize: 20.0,
                    fontWeight: FontWeight.bold,
                    letterSpacing: 2.0,
                    color: Colors.orange[600],
                    fontFamily: 'SendFlowers',
                  ),
                ),

              ),

              Container(
                padding: EdgeInsets.all(20.0),
//padding: EdgeInsets.fromLTRB(10.0,15.0,10.0,15.0),
//padding: EdgeInsets.symmetric(20.0),
                margin: EdgeInsets.all(20.0),
                color: Colors.green,

                child: Text('Hello again2',
                  style: TextStyle(
                    fontSize: 20.0,
                    fontWeight: FontWeight.bold,
                    letterSpacing: 2.0,
                    color: Colors.green[600],
                    fontFamily: 'SendFlowers',
                  ),
                ),

              ),
            ],
          ),
        ],
      ),

      floatingActionButton: FloatingActionButton(
        onPressed: () {
          setState(() {
            ninjaLevel += 1;
          });
        },
        child: Text('click'),
        backgroundColor: Colors.orange,
        hoverColor: Colors.redAccent,
      ),
      backgroundColor: Colors.white,
    );
  }
}








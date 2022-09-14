# My-Resume-Code
Resume Apk.
import 'package:flutter/material.dart';
void main() {
  runApp(MaterialApp(
    home: Demo(),
  ));
}

class Demo extends StatelessWidget{
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: Center(child: Text("Resume")),),
      body:SingleChildScrollView(
        child: Container(
          color: Colors.grey[300],
          child: Column(
            children: [
              //SizedBox(height: 20),
              SingleChildScrollView(
                scrollDirection: Axis.horizontal,
                child: Row(
                  children: [
                    Container(
                      //padding: EdgeInsets.fromLTRB(10.0, 0, 0,0),
                        height: 200,
                        width: 100,
                        child: Image.network("https://lh3.googleusercontent.com/a-/AOh14GigJu3AAmjhiAPXFymQY_xdXQUu7Q0v0iH7WSiwnQ=s288-p-rw-no")),
                    Container(
                      padding: EdgeInsets.fromLTRB(10.0, 0, 0,0),
                      //margin: EdgeInsets.fromLTRB(1.0, 0, 0, 0),
                      child: Text("Name:- Ghanshyam Banait\n"
                          "Email Id:- ghanshyambanait@gmail.com \n"
                          "Mobile No.:- 7350832238\n",
                        style: TextStyle(fontSize: 20,fontWeight: FontWeight.bold),),
                    ),
                  ],
                ),
              ),
              Divider(
                color: Colors.black,
                thickness: 0.9,
              ),
              SizedBox(height: 10,),
              Container(
                padding: EdgeInsets.fromLTRB(10.0, 0, 0,0),
                //margin: EdgeInsets.fromLTRB(1.0, 0, 0, 0),
                child: Text("Objective",
                  style: TextStyle(fontSize: 20,fontWeight: FontWeight.bold),),
              ),
              Container(
                padding: EdgeInsets.fromLTRB(10.0, 0, 0,0),
                //margin: EdgeInsets.fromLTRB(1.0, 0, 0, 0),
                child: Text("To have a challenging career, as I am fresher seeking for the opportunity to prove my skills and \n"
                    "Investing best of my knowledge in the growth of the organization.",
                  style: TextStyle(fontSize: 20),),
              ),
              Divider(
                color: Colors.black,
                thickness: 0.9,
              ),

              Container(
                color: Colors.grey[300],
                padding: EdgeInsets.all(20.0),
                child: Table(
                  border: TableBorder.all(color: Colors.black),
                  children: [
                    TableRow(children: [
                      Center(child: Text('Qaulification',style: TextStyle(fontWeight: FontWeight.bold,fontSize: 15),)),
                      Center(child: Text('Pass Year',style: TextStyle(fontWeight: FontWeight.bold,fontSize: 15),)),
                      Center(child: Text('Institute',style: TextStyle(fontWeight: FontWeight.bold,fontSize: 15),)),
                      Center(child: Text('Marks %',style: TextStyle(fontWeight: FontWeight.bold,fontSize: 15),)),
                    ]),
                    TableRow(children: [
                      Center(child: Text('B.Tech (ENTC')),
                      Center(child: Text('2023 -appearing 3rd year 2022')),
                      Center(child: Text('Govt.Engineering college , Jalgaon. ')),
                      Center(child: Text('----')),
                    ]),
                    TableRow(children: [
                      Center(child: Text('Diploma ENTC ')),
                      Center(child: Text('2020')),
                      Center(child: Text('Government polytechnic,Jalgaon. ')),
                      Center(child: Text('88.53%')),
                    ]),

                    TableRow(children: [
                      Center(child: Text('SSC ')),
                      Center(child: Text('2017')),
                      Center(child: Text('RDMVK.(NASHIK BOARD).')),
                      Center(child: Text('87%')),
                    ]),
                  ],
                ),
              ),
              SizedBox(height: 10,),
              Container(
                padding: EdgeInsets.fromLTRB(10.0, 0, 0,0),
                //margin: EdgeInsets.fromLTRB(1.0, 0, 0, 0),
                child: Text("In Plant Training ",
                  style: TextStyle(fontSize: 20,fontWeight: FontWeight.bold),),
              ),
              Container(
                padding: EdgeInsets.fromLTRB(10.0, 0, 0,0),
                //margin: EdgeInsets.fromLTRB(1.0, 0, 0, 0),
                child: Text("ACE TECHNO SERVICES,Aurangabad 431005.\n"
                    ,
                  style: TextStyle(fontSize: 20),),
              ),

              Divider(
                color: Colors.blue,
                thickness: 0.9,
              ),
              SizedBox(height: 10,),
              Container(
                padding: EdgeInsets.fromLTRB(10.0, 0, 0,0),
                //margin: EdgeInsets.fromLTRB(1.0, 0, 0, 0),
                child: Text("Computer Skills",
                  style: TextStyle(fontSize: 20,fontWeight: FontWeight.bold),),
              ),
              Container(
                padding: EdgeInsets.fromLTRB(10.0, 0, 0,0),
                //margin: EdgeInsets.fromLTRB(1.0, 0, 0, 0),
                child: Text(" Languages Known: -  C, Python,Android(Dart,Flutter)",

                  style: TextStyle(fontSize: 20),),
              ),
              Divider(
                color: Colors.blue,
                thickness: 0.9,
              ),
              SizedBox(height: 10,),
              Container(
                padding: EdgeInsets.fromLTRB(10.0, 0, 0,0),
                //margin: EdgeInsets.fromLTRB(1.0, 0, 0, 0),
                child: Text("Personal Skills",
                  style: TextStyle(fontSize: 20,fontWeight: FontWeight.bold),),
              ),
              Container(
                padding: EdgeInsets.fromLTRB(10.0, 0, 0,0),
                //margin: EdgeInsets.fromLTRB(1.0, 0, 0, 0),
                child: Text(" Positive Attitude. \n"
                    " Quick Learner.\n",

                  style: TextStyle(fontSize: 20),),
              ),



              SizedBox(height: 10,),
              Container(
                padding: EdgeInsets.fromLTRB(10.0, 0, 0,0),
                //margin: EdgeInsets.fromLTRB(1.0, 0, 0, 0),
                child: Text("Personal Details",
                  style: TextStyle(fontSize: 20,fontWeight: FontWeight.bold),),
              ),
              Container(
                padding: EdgeInsets.fromLTRB(10.0, 0, 0,0),
                //margin: EdgeInsets.fromLTRB(1.0, 0, 0, 0),
                child: Text(" Date of Birth : 05 11 2001\n"
                    " Hobbies :Cricket,Listening,Music,Quotes.\n"
                    " Languages :Marathi, English, Hindi.",
                  style: TextStyle(fontSize: 20),),
              ),
              SizedBox(height: 10,),
              Divider(
                color: Colors.blue,
                thickness: 0.9,
              ),
              SizedBox(height: 10,),
              Container(
                padding: EdgeInsets.fromLTRB(10.0, 0, 0,0),
                //margin: EdgeInsets.fromLTRB(1.0, 0, 0, 0),
                child: Text("Declaration",
                  style: TextStyle(fontSize: 20,fontWeight: FontWeight.bold),),
              ),
              Container(
                padding: EdgeInsets.fromLTRB(10.0, 0, 0,0),
                //margin: EdgeInsets.fromLTRB(1.0, 0, 0, 0),
                child: Text(" I hereby declare that the information given above is true to the best of my knowledge.",
                  style: TextStyle(fontSize: 20),),
              ),
              Container(
                child: Row(
                  children: [
                    Container(
                      padding: EdgeInsets.fromLTRB(10.0, 0, 0, 0),
                      child: Text("Date:", style: TextStyle(fontSize: 20),),
                    ),
                    SizedBox(width: 150,),
                    Container(
                      padding: EdgeInsets.fromLTRB(10.0, 0, 10.0, 0),
                      child: Text("Yours Faithfully, ", style: TextStyle(fontSize: 20),),
                    ),
                  ],
                ),

              ),
              Container(
                child: Row(
                  children: [
                    Container(
                      padding: EdgeInsets.fromLTRB(10.0, 0, 0, 0),
                      child: Text("Place:", style: TextStyle(fontSize: 20),),
                    ),
                    SizedBox(width: 150,),
                    Container(
                      padding: EdgeInsets.fromLTRB(10.0, 0, 10.0, 0),
                      child: Text("Jalgaon.", style: TextStyle(fontSize: 20),),
                    ),
                  ],
                ),

              ),
              Container(
                child: Row(
                  children: [
                    SizedBox(width: 250,),
                    Container(
                      padding: EdgeInsets.fromLTRB(10.0, 0, 10.0, 0),
                      child: Text("Ghaanshyam Banait", style: TextStyle(fontSize: 20),),
                    ),
                  ],
                ),

              ),
              Container(
                child: Row(
                  children: [
                    SizedBox(width: 230,),
                    Container(
                      padding: EdgeInsets.fromLTRB(10.0, 0, 10.0, 0),
                      child: Text(" Signature", style: TextStyle(fontSize: 20),),
                    ),
                  ],
                ),

              ),
              SizedBox(height: 10,),
              Divider(
                color: Colors.blue,
                thickness: 0.9,
              ),

            ],
          ),
        ),
      ),
    );
  }
}

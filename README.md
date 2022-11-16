# -4
Страница 147 номер 18

Создать класс Программа Передач с внутренним классом, с помощью объектов которого можно хранить информацию о названии телеканалов и программ

package bilet7;

import java.util.Scanner;

publicclass Department {

publicstatic Scanner ob=new Scanner(System.in);

public info info;

public String city;

public Department(){

System.out.print("введитеназваниеотделафирмы");

setDepartment(ob.next());

info=new info();

}

public String getDepartment(){

returncity;
}
publicvoidsetDepartment(String city){
this.city=city; 

}

publicclassinfo{

intpr,st,sq;

publicinfo(){

System.out.print("введите количество должностей отдела:");

setPr(ob.nextInt());

System.out.print("количество сотрудников:");

setSt(ob.nextInt());

System.out.print("введите количество филиалов:");

setSq(ob.nextInt());   

}

publicintgetPr(){

returnpr;

}

publicvoidsetPr(int pr){

this.pr=pr;

}

publicintgetSt(){

returnst;

}

publicvoidsetSt(int st){

this.st=st;

}

publicintgetSq(){

returnsq;

}

publicvoidsetSq(int sq){

this.sq=sq;

}
publicvoidprint(){

System.out.print("Нафирме"+" "+getDepartment()+""+getPr()+"сотрудников"+getSt()+"должностей"+getSq()+"филиалов");

}

}

staticpublicvoidmain(String[]args){

Department ct=new Department();

ct.info.print();

}

}


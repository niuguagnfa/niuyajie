# niuyajie
mycode
public class student {
	//静态的数据
	private String name;
	int id;
	int age;
	int weight;
	//动态的行为
	public void study(){
		System.out.println(name+"在学习");
	}

	public void sayHello(String sname){
		System.out.println(name+"向"+sname+"说你好");
	}
	public void saylike(String wname){
		System.out.println(name+"对"+wname+"爱你一辈子");
	}
	public static void main(String[] args){
		student s1 = new student();
		s1.name ="小牛";
		s1.study();
		s1.sayHello("稳稳");
		s1.saylike("稳稳");
	}
}

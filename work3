import java.util.HashSet;
import java.util.Iterator;
import java.util.Scanner;


public class work3 { //204
public static void main(String args[]){
	HashSet stu = new HashSet();
	Scanner in = new Scanner(System.in);
		String name;
		System.out.println("請一次輸入學生姓名，空行代表結束");
		boolean goon = true;
				while (goon){
					name =in.nextLine();
					if(name.length()> 0)
						stu.add(name);
					else
						goon = false;
				}
				System.out.println("請輸入要刪除的學生姓名,空行代表結束");
				goon = true;
				while (goon){
					name = in.nextLine();
					if (name.length() > 0){
						if(stu.remove(name))
							System.out.println("刪除成功:" + name);
						else 
							System.out.println("沒有找到此人" + name);
					}else
						goon = false;
				}
				System.out.println("剩下的學生還有");
				Iterator iterator = stu.iterator();
				while(true){
					if(iterator.hasNext()){
						System.out.println(iterator.next().toString());
						
					}else {
						break;
					}
				}in.close();
}
	
}


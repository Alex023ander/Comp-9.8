# Comp-9.8

public class English extends Curriculum{
    public String lev;
	public String teach;
	public English(String title, int number, String description, String department, String level, String teacher) {
		super(title, number, description, department);
		lev = level;
		teach = teacher;
	 }
	 public void getLevel() {
		 System.out.println(lev);
	 }
	 public void getTeacher() {
		 System.out.println(teach);
	 }
}

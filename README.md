# Comp-9.8

public class Curriculum {
    private String t="", d="",de="";
    private int n=0;
    public Curriculum(String title,int number,String description,String department){
        t = title;
        n = number;
        d = description;
        de = department;
        
    }
    public String getTitle(){
        return t;
    }
    public String getDescription(){
        return d;
    }
    public String getDepartment(){
        return de;
    }
    public int getNumber(){
        return n;
    }
    @Override
    public String toString(){
        return "Title: "+t+", \nDescription: "+d+", \nNumber: "+n+", \nDepartment: "+de;
    }
}
